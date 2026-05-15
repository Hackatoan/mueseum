[![Buy Me A Coffee](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://buymeacoffee.com/hackatoa)

# mueseum

A digital museum that turns a folder of photos into a beautifully styled, browsable gallery. No server required — just a Python script and a browser.

## Quick start

1. Drop your photos into the `photos/` folder
   - Supported: `.jpg`, `.jpeg`, `.png`, `.gif`, `.webp`, `.avif`, `.svg`
2. Generate the gallery:
   ```bash
   python generate.py
   ```
3. Open `index.html` in any browser

## Features

- Museum-style dark theme with gold accents and ornate frames
- Responsive grid layout
- Full-screen lightbox on click
- Keyboard accessible (Tab to navigate, Enter/Space to open, Escape to close)
- Lazy-loading for fast initial load
- Photo titles auto-derived from filenames

## File structure

```
mueseum/
├── photos/       ← drop images here
├── generate.py   ← run to rebuild the gallery
└── index.html    ← generated output
```

---

[hackatoa.com](https://hackatoa.com) · [GitHub](https://github.com/Hackatoan) · [Buy Me A Coffee](https://buymeacoffee.com/hackatoa)
