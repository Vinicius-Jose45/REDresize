<p align="center">
  <h1 align="center">REDresize</h1>
  <p align="center">A browser-based image resizing & conversion web app with a retro CLI interface.</p>
  <p align="center">
    English · <a href="README.pt-BR.md">Português</a>
  </p>
  <p align="center">
    Process, convert, and inspect images completely client-side with a cyberpunk terminal aesthetic.
  </p>
</p>

---

## 🚀 Overview

**REDresize** is a web application focused on image resizing and conversion, featuring a command-line interface (CLI) styled theme. The entire application operates 100% client-side in the browser using raw HTML, vanilla JavaScript, and Tailwind CSS — ensuring fast processing without uploading your files to any external server.

---

## ✨ Features

### 📸 Single Mode (Individual Editing)
* **Import Options:** Drag-and-drop, file picker, or direct paste from clipboard (`CTRL+V`).
* **Format Conversion:** Convert between PNG, JPEG, WEBP, and ICO formats with customizable quality control.
* **Resolution Control:** Quick preset buttons (from 16x16 micro-favicons up to 1920x1080 Full HD) plus manual width/height input with aspect ratio locking.
* **Rendering Options:**
  * Canvas fill modes: *Cover*, *Contain*, and *Stretch*.
  * Background color picker.
  * Resampling algorithm selection: Switch between high-quality (*Bicubic*) and pixel-sharp non-blurred rendering (*Nearest Neighbor*).
* **Real-time Monitoring:** Dual output panel featuring real-scale image preview and a *Pixel Magnifier* lens. Includes live estimation of the output file size (Bytes, KB, MB).
* **Export Options:** Download image, copy image data directly to clipboard, or export an **Icon Kit** (a `.zip` containing six standard icon sizes generated via JSZip).

### 📦 Batch CLI (Bulk Processing)
* Drag and drop multiple images at once.
* Parallel bulk resizing to target resolutions.
* Package and download all processed output images into a single `.zip` archive.

---

## 🎨 Design & Aesthetics

* **Cyberpunk & Technical Aesthetic:** Fira Code monospace typography with dark grey and neon red accents.
* **Retro Terminal FX:** Terminal action glow effects (`cmd-glow`) and an optional CRT scanline overlay simulating vintage monitors.
* **Theme Support:** Seamless toggle between Dark and Light mode.

---

## 🛠️ Tech Stack

* **HTML5**
* **Vanilla JavaScript** (ES6+)
* **Tailwind CSS**
* **JSZip** (Zip archiving)

---

## ⚙️ Getting Started

Since REDresize runs entirely in the browser, no backend setup or build step is required!

1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/REDresize.git](https://github.com/your-username/REDresize.git)