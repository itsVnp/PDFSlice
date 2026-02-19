# PDF Slice

Convert PDF pages to high-quality images, or combine images into one PDF — **100% in your browser**. No uploads, no server, no account. Your files never leave your device.

**Live:** [pdfslice.com](https://pdfslice.com)

Made in India · Built with love

## Features

- **PDF → IMG** — Export each PDF page as an image (JPEG). Adjust resolution scale and image quality. Download all pages as a ZIP.
- **IMG → PDF** — Combine multiple images (JPEG, PNG, WebP, GIF) into one PDF. Drag to reorder, choose page size (fit, A4, Letter), add or remove images.
- **Private** — Everything runs locally. No data is sent to any server. We don’t collect, store, or access your files, cookies, or any data.
- **No account** — Use the tool instantly. No sign-up or login.
- **Light / dark theme** — Toggle in the header; preference is saved.

## Why PDF Slice?

- **100% local processing** — Your files are opened and converted in your browser. No upload, no cloud.
- **No account or sign-up** — Open the page, pick your files, and convert.
- **Fast and free** — No server queues. Conversion happens on your machine.
- **We never collect, store, or access your data** — No files, no cookies, no tracking. Your data stays completely yours.

## How to run locally

1. Clone the repo:
   ```bash
   git clone https://github.com/itsVnp/PDFSlice.git
   cd PDFSlice
   ```
2. Open `index.html` in your browser (no build step or server required):
   ```bash
   open index.html
   ```
   Or use a local static server if you prefer:
   ```bash
   npx serve .
   ```

## Deploy

The app is a single static HTML file. Deploy to any static host:

- **Vercel / Netlify / GitHub Pages** — Connect the repo; each push to `main` triggers a new deployment. No environment variables or build step needed.
- **Any web server** — Serve the directory; `index.html` is the entry point.

## Tech

- [PDF.js](https://mozilla.github.io/pdf.js/) (Mozilla) — PDF rendering in the browser
- [jsPDF](https://github.com/parallax/jsPDF) — Create PDF from images
- [JSZip](https://stuk.github.io/jszip/) — ZIP download for multiple images

No backend. All processing happens in the browser.

## Developer

**Vivekanand**

- [LinkedIn](https://www.linkedin.com/in/itsvnp/)
- [vivekanand.me](https://vivekanand.me)

## License

MIT
