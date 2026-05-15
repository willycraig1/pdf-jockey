# PDF Jockey

A self-contained, single-file HTML app for visually merging and reorganizing PDF files — a lightweight alternative to Adobe Acrobat for everyday document work.

Open `pdf-jockey.html` in any modern browser. No install, no account, no server. Files never leave your machine.

---

## Features

- **Drop PDFs, JPGs, or PNGs** — every page renders as a thumbnail in a scrollable grid
- **Drag to reorder** — drag individual pages or multi-select and drag the group
- **Multi-select** — click, Ctrl/⌘+click, Shift+click, or Cmd+A to select ranges
- **Per-page controls** — delete (×), rotate left (↺), rotate right (↻) on hover
- **Lightbox preview** — double-click any thumbnail for a full-size carousel view with peek of adjacent pages
- **Export** — downloads a single merged PDF with all reorders and rotations applied

## Usage

1. Download `pdf-jockey.html`
2. Open it in Chrome, Firefox, Safari, or Edge
3. Drop your PDFs or images onto the page
4. Reorder, rotate, and delete pages as needed
5. Click **Export PDF**

## Tech stack

All dependencies load from CDN — no build step, no `node_modules`.

| Library | Purpose |
|---|---|
| [PDF.js](https://mozilla.github.io/pdf.js/) v3.11.174 | Renders PDF pages to canvas for thumbnails and preview |
| [pdf-lib](https://pdf-lib.js.org/) v1.17.1 | Loads, manipulates, and assembles the exported PDF |

## Keyboard shortcuts

| Key | Action |
|---|---|
| Double-click thumbnail | Open lightbox preview |
| ←/→ arrow keys | Navigate lightbox |
| Esc | Close lightbox / cancel drag |
| Cmd/Ctrl+A | Select all pages |
| Delete / Backspace | Delete selected pages |
| Cmd/Ctrl+Shift+E | Export PDF |
