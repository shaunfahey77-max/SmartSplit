[README.md](https://github.com/user-attachments/files/24612539/README.md)
# SmartSplit Brand Assets (3‑Ring System) — Locked

This folder is the **single source of truth** for SmartSplit logos, icons, and favicons.

## ✅ Rules (so we never break this again)
- **All SmartSplit marks must use the 3‑ring system.** No 2‑ring variants.
- **Web usage:** prefer **SVG** for crisp rendering at any size.
- **Do not recolor logos with CSS filters.** Use the provided color/white files.
- **Do not move/rename files** without updating references in `index.html` and the brand guide.

---

## Folder structure
```
assets/brand/
  svg/        # PRIMARY for web (sharp)
  logos/      # PNG exports (responsive sizes)
  icons/      # App/UI icons (square)
  favicon/    # Favicons + webmanifest assets
```

---

## Primary assets
### Header logo (color)
Use on light backgrounds:
- `assets/brand/svg/smartsplit-horizontal-3rings.svg`

### Header logo (white)
Use on dark/gradient headers:
- `assets/brand/svg/smartsplit-horizontal-3rings-white.svg`

### App/UI icon
- Color: `assets/brand/svg/smartsplit-icon-3rings.svg`
- White: `assets/brand/svg/smartsplit-icon-3rings-white.svg`

---

## Recommended HTML snippets

### Header logo (SVG, best)
```html
<a class="brand" href="./index.html" aria-label="SmartSplit Home">
  <img class="brand-logo"
       src="./assets/brand/svg/smartsplit-horizontal-3rings-white.svg"
       alt="SmartSplit" decoding="async" />
</a>
```

### Icon usage (SVG)
```html
<img src="./assets/brand/svg/smartsplit-icon-3rings.svg" alt="" aria-hidden="true">
```

### Favicons
```html
<link rel="icon" href="./assets/brand/favicon/favicon.ico">
<link rel="icon" type="image/png" sizes="32x32" href="./assets/brand/favicon/favicon-32.png">
<link rel="apple-touch-icon" sizes="180x180" href="./assets/brand/favicon/favicon-180.png">
```

---

## PNG exports (if you need them)
- Horizontal logo: 800 / 1200 / 2000 px wide in `assets/brand/logos/`
- Icon: 128 / 256 / 512 / 1024 px in `assets/brand/icons/`
- Favicons: 16 / 32 / 48 / 64 / 180 / 192 / 512 in `assets/brand/favicon/`

Updated: 2026-01-14
