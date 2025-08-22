# QR Code from URL — Single File

A lightweight, single-page web app that generates QR codes from any URL.  
All processing happens **entirely in your browser**—no server, no tracking, no data leaving your machine.

![Screenshot](screenshot.png) <!-- Optional: add a screenshot if you want -->

---

## ✨ Features
- **Single file HTML** — just open it in your browser, no install required.
- **Client-side only** — safe for offline or private use.
- **Customizable output**:
  - Size (128–2048px)
  - Quiet zone (white margin around the QR)
  - Error correction levels (L, M, Q, H)
- **Export options**:
  - Download PNG
  - Copy QR image to clipboard
  - Generate shareable permalink with pre-filled options
- **Keyboard shortcut**: Press <kbd>Enter</kbd> to generate quickly.

---

## 🚀 Getting Started

1. Clone or download this repository:
   ```bash
   git clone https://github.com/yourusername/qr-code-singlefile.git
   cd qr-code-singlefile
   ```

2. Open the file in your browser:
   ```
   single_file_qr_code_generator.html
   ```

3. Paste a URL, click **Generate**, and you’re set.

---

## 🔧 Offline Build

By default, this app loads the [qrcodejs](https://github.com/davidshimjs/qrcodejs) library from a CDN.  
If you need a 100% offline build (e.g., for air-gapped systems), copy the contents of `qrcode.min.js` into the HTML file and replace the `<script src=...>` tag with an inline `<script>` block.  
The rest of the app already works without modification.

---

## 📂 Deployment

Because it’s just one HTML file, you can:
- Host it on GitHub Pages (`/qr.html` or similar).
- Drop it on your personal server (Nginx, Apache, etc.).
- Carry it on a USB stick for offline use.

---

## 📝 License

This project is released under the MIT License.  
QR code generation is powered by [qrcodejs by davidshimjs](https://github.com/davidshimjs/qrcodejs) (MIT).

---

## 🙌 Credits
- **Design & Implementation:** Inspired by the idea of useful single-page tools.
- **QR Code Library:** [qrcodejs](https://github.com/davidshimjs/qrcodejs)

