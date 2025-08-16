# 📸 SnapHunt

SnapHunt is a lightweight Python tool for image intelligence gathering (IMGINT).  
It extracts metadata, generates cryptographic hashes, fetches system and host info, and builds direct reverse image search links — all in one report.

![SnapHunt Screenshot](https://i.ibb.co/4ggprtJg/Screenshot-2025-08-14-161205.png)

---

## 🚀 Features
- 📂 **Image Metadata Extraction** (format, size, mode)
- 🔑 **Cryptographic Hashes** (MD5, SHA1, SHA256)
- 🔍 **Reverse Image Search Links**:
  - Google Lens
  - Yandex
  - Bing
  - TinEye
  - SauceNAO
- 📑 **Automatic Report Generation** (timestamped `.txt` file)

---

## 📥 Installation

```bash
git clone https://github.com/yourusername/SnapHunt.git
cd SnapHunt
pip install -r requirements.txt
 
⚡ Usage
python snaphunt.py path/to/image.png
