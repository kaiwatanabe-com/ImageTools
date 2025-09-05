# Redact-It — Secure Client-Side Photo Redactor

**Redact-It** is a lightweight, privacy-first tool for securely redacting images. It runs entirely in your browser with **no server-side processing**. All exports are flattened and stripped of EXIF metadata.

## ✨ Features

- 📂 **Local-only processing** — works offline, no data leaves your device  
- 🖌️ **Redaction tools**: Rectangle, Ellipse, Freehand, Polygon  
- 🎨 **Styles**: Black fill, Mosaic, Blur (with high-assurance mode)  
- ↩️ **Undo / Redo** history with reset to original  
- 💾 **Export options**: PNG (lossless), JPEG, WEBP with quality control and scale  
- 🧨 **Self-destruct mode** to wipe images and revoke temporary URLs  
- ⚙️ **Advanced controls**: Mask expansion, export scaling, auto-fit, confirmation dialogs  

## 🔒 Security & Privacy

- Runs fully **client-side** (no network calls allowed via CSP)  
- Images are handled in memory and never uploaded  
- Exports are **flattened & EXIF-free**  
- Supports **panic wipe** (`Shift+Esc`) to immediately clear all data  

## ⌨️ Shortcuts

- `O` — Open image  
- `R / E / F / P` — Rect / Ellipse / Freehand / Polygon tools  
- `B / M / G` — Black / Mosaic / Blur styles  
- `Ctrl/Cmd+Z` — Undo  
- `Ctrl/Cmd+Shift+Z` or `Ctrl/Cmd+Y` — Redo  
- `S` — Save image  
- `Shift+Esc` — Self-destruct  

## 🚀 Usage

1. Open `imageblur.html` in a modern browser (Chrome, Firefox, Brave, Safari).  
2. Drag & drop an image or click **Open**.  
3. Select a **tool** and **style**, then redact areas of the image.  
4. Adjust blur/mosaic/brush size with sliders.  
5. Save your redacted image in PNG, JPEG, or WEBP.  

## 🛠 Development

The project is a single static HTML file. To run locally:

```bash
git clone https://github.com/yourname/redact-it.git
cd redact-it
open imageblur.html
```

No dependencies required. Works offline out of the box.

## 📜 License

MIT License. 
