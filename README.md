# KeyHunterSM4

## SM4 Key Extractor for libUE4.so

A lightweight tool to extract **SM4 encryption keys** from `libUE4.so` using **Termux** and **Mono**.  
Designed for research and security analysis.

---

## Requirements
- Android device
- Termux
- Mono runtime

---

## Installation (Termux)

```bash
pkg install unstable-repo
pkg install mono
```

---

## Folder Structure

The tool and the library **must be in the same directory**.

```
KeyHunterSM4/
├── sm4key.exe
├── libUE4.so
└── README.md
```

> Lazem `sm4key.exe` w `libUE4.so` ykono fe nafs el-folder.

---

## Usage

```bash
mono sm4key.exe
```

The tool will automatically detect `libUE4.so` and extract SM4 keys.

---

## Architecture Support
- armv7 (32-bit)
- arm64 (64-bit)

No additional configuration required.

---

## Telegram
For updates and support:

https://t.me/Theend2032

---

## Legal Disclaimer
This tool is intended for **research and educational purposes only**.  
Do not use it on proprietary software or games without permission.  
You are responsible for its usage.

---

## License
MIT License
