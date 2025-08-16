# 📸 SnapHunt

SnapHunt is a lightweight Python tool for **image intelligence gathering (IMGINT)**.  
It extracts metadata, generates cryptographic hashes, fetches system and host info, and builds direct reverse image search links — all in one report.

![SnapHunt Screenshot](https://i.ibb.co/4ggprtJg/Screenshot-2025-08-14-161205.png)

---

## 🚀 Features
- 📂 **Image Metadata Extraction**  
  - Format, size, and mode
- 🔑 **Cryptographic Hashes**  
  - MD5, SHA1, SHA256
- 🌍 **GPS Data Extraction** (if available)  
  - Latitude, Longitude, Google Maps link
- 🔍 **Reverse Image Search Links**  
  - Google Lens  
  - Yandex  
  - Bing  
  - TinEye  
  - SauceNAO
- 📑 **Automatic Report Generation**  
  - Timestamped `.txt` file
---

## 📥 Installation

```bash
git clone https://github.com/yourusername/SnapHunt.git
cd SnapHunt
pip install -r requirements.txt
```

## ⚡ Usage
```bash
python snaphunt.py path/to/image.png
```

This tool is for educational and research purposes only.
The author is not responsible for any misuse.
