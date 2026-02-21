# ⚡ PDF Ultra Converter

> **The world's most powerful free PDF toolkit — runs entirely in your browser.**

[![PWA](https://img.shields.io/badge/PWA-Installable-blue?logo=googlechrome)](https://your-username.github.io/pdf-ultra)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)
[![Zero Tracking](https://img.shields.io/badge/Tracking-None-success)](README.md)
[![No Server](https://img.shields.io/badge/Server-None-orange)](README.md)

---

## ✨ Features

### 📄 PDF → Anything (11 formats)
| Conversion | Output | Description |
|---|---|---|
| PDF → Word | `.docx` | Full Word document with text extracted |
| PDF → Excel | `.xlsx` | Spreadsheet with all page content |
| PDF → PowerPoint | `.pptx` | Slide for each page |
| PDF → JPG | `.zip` | Each page as JPEG image |
| PDF → PNG | `.zip` | Each page as PNG image |
| PDF → TXT | `.txt` | Plain text extraction |
| PDF → HTML | `.html` | Web-ready HTML page |
| PDF → Markdown | `.md` | Formatted markdown document |
| PDF → CSV | `.csv` | Table/spreadsheet data |
| PDF → ePub | `.epub` | eBook format |
| PDF → RTF | `.rtf` | Rich Text Format |

### 🔄 Anything → PDF (7 formats)
| Input | Output | Description |
|---|---|---|
| JPG/PNG/WebP | `.pdf` | Image to PDF with layout options |
| TXT | `.pdf` | Plain text formatted as PDF |
| HTML | `.pdf` | HTML page to PDF |
| Markdown | `.pdf` | Markdown with heading styles |
| CSV | `.pdf` | Table-formatted PDF |
| Excel (XLSX) | `.pdf` | Spreadsheet to PDF |
| RTF | `.pdf` | Rich text to PDF |

### 🛠️ PDF Tools (5 tools)
| Tool | Description |
|---|---|
| Merge PDFs | Combine multiple PDF files into one |
| Split PDF | Extract every page as separate PDF |
| Rotate Pages | Rotate all pages 90°, 180°, or 270° |
| Add Watermark | Text watermark with custom opacity |
| Compress PDF | Reduce file size with optimization |

---

## 🔒 Privacy First

**Your files NEVER leave your device.**

All processing happens 100% client-side in your browser using:
- [PDF.js](https://mozilla.github.io/pdf.js/) by Mozilla — PDF rendering
- [pdf-lib](https://pdf-lib.js.org/) — PDF creation & manipulation
- [jsPDF](https://github.com/parallax/jsPDF) — PDF generation
- [SheetJS](https://sheetjs.com/) — Excel/CSV parsing
- [JSZip](https://stuk.github.io/jszip/) — ZIP compression

---

## 📲 Install as Native App (PWA)

PDF Ultra is a **Progressive Web App**. When you open it in Chrome/Edge/Safari, a banner appears at the bottom asking you to **INSTALL APP**. After installing:

- 📱 App icon appears on your home screen / desktop
- ⚡ Works completely **offline**
- 🚀 Opens instantly like a native app
- 🔒 All processing still private

### Supported Install Platforms
| Platform | Browser | Install Method |
|---|---|---|
| Android | Chrome | Banner prompt → Install |
| iPhone/iPad | Safari | Share → Add to Home Screen |
| Windows | Chrome/Edge | Address bar install icon |
| macOS | Chrome/Edge | Address bar install icon |
| Linux | Chrome | Address bar install icon |

---

## 🚀 Deploy to GitHub Pages

1. **Fork this repo**
2. Go to **Settings → Pages**
3. Set Source to **main branch, / (root)**
4. Done! Your app is live at `https://your-username.github.io/pdf-ultra`

### Or deploy to Netlify/Vercel (one click)
Just connect your GitHub repo — it's pure static HTML, no build step needed.

---

## 📁 Project Structure

```
pdf-ultra/
├── index.html      ← Complete single-page app (all JS + CSS inline)
├── manifest.json   ← PWA manifest (install config)
├── sw.js           ← Service Worker (offline support)
├── icon-192.png    ← App icon (192×192)
├── icon-512.png    ← App icon (512×512)
└── README.md       ← This file
```

---

## 🛒 Publishing to App Stores

### Google Play Store (Android)
Use [PWABuilder](https://www.pwabuilder.com/) to wrap your hosted PWA as an Android APK:
1. Enter your deployed URL
2. Click "Build for Android"
3. Download the signed APK
4. Submit to [Google Play Console](https://play.google.com/console)

### Microsoft Store (Windows)
PWABuilder also supports Windows Store packaging:
1. Enter your URL on PWABuilder
2. Select Windows package
3. Submit to Microsoft Partner Center

### Apple App Store (iOS)
Use [PWABuilder iOS packaging](https://www.pwabuilder.com/ios) or manually wrap with Xcode's WKWebView.

---

## 🛠️ Local Development

No build tools needed. Just open `index.html` in your browser:

```bash
git clone https://github.com/your-username/pdf-ultra
cd pdf-ultra

# Option 1: Python
python -m http.server 8000

# Option 2: Node
npx serve .

# Option 3: VS Code
# Install "Live Server" extension and click "Go Live"
```

---

## 📜 License

MIT License — free for personal and commercial use.

---

## ⭐ Star History

If this helped you, please give it a star! It helps others find the project.

---

*Built with ⚡ by the open source community. No ads. No tracking. Free forever.*
