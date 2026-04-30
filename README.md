# mueseum
A digital museum that turns a folder of photos into a beautifully styled, browsable gallery.

## Quick start

1. **Add your photos** to the `photos/` folder.  
   Supported formats: `.jpg`, `.jpeg`, `.png`, `.gif`, `.webp`, `.avif`, `.svg`

2. **Generate the gallery:**
   ```bash
   python generate.py
   ```

3. **Open** `index.html` in any web browser — no server required.

## Features

- Museum-style dark theme with gold accents and ornate frames
- Responsive grid layout (auto-fills based on screen width)
- Click any photo to open a full-screen lightbox viewer
- Keyboard accessible (Tab to navigate, Enter/Space to open, Escape to close)
- Lazy-loading images for fast initial page load
- Photo titles are derived automatically from file names

## File structure

```
mueseum/
├── photos/          ← drop your images here
├── generate.py      ← run to rebuild the gallery
├── index.html       ← generated output (open in a browser)
└── README.md
```
