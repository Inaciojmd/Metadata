
![Banner Preview](https://i.ibb.co/23tvfdWY/111.png)  


# 🛡️ Metadata Destroyer v1.0

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Security](https://img.shields.io/badge/Security-Military--Grade-red)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20macOS-lightgrey)

**Metadata Destroyer** is a **military-grade metadata cleaner** that removes sensitive metadata from **images, videos, and audio** files securely and irreversibly.  
It uses a **multi-stage cleaning process**, cryptographic filename randomization, and secure overwrite to ensure data cannot be recovered.

---

## ✨ Features
- **Multi-Stage Cleaning**:
  - Images → Removes EXIF, XMP, ICC, IPTC metadata
  - Audio → Removes ID3, XMP, RIFF tags
  - Video → Removes QuickTime, EXIF, and other embedded metadata
- Secure Overwrite — Original files are destroyed after cleaning
- Cryptographic Random Filename Generator
- Parallel Processing** for bulk cleaning
- Military-Grade Verification with ExifTool and FFmpeg
- Cross-Platform — Works on Windows, Linux, and macOS

---

## 📦 Installation

 📂 Clone the Repository
```bash
git clone https://github.com/Inaciojms/Metadata.git
cd metadata
python3 metadata.py
```

🏗️ Create a Virtual Environment
```bash
  python3 -m venv venv
  source venv/bin/activate
```

### 1. Install Python Dependencies
Requires **Python 3.8+**:
```bash
pip install -r requirements.txt
```





