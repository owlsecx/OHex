# 🦉 OHex

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OForensics-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.1.0-cyan?style=flat-square"/>
</p>

> **OHex** — Professional Hex Editor & Binary Forensics Toolkit

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

OHex is a professional hex editor and binary forensics toolkit for viewing, hashing, entropy mapping, and signature carving. Investigators can open artefacts in a TUI-oriented workflow or run quick CLI probes for info, hashes, entropy, and carved signatures. Built for defensive binary triage on Linux.

---

## ✨ Features

- Hex viewer/editor oriented binary inspection
- Quick --info JSON summary for a target file
- Hash and entropy probes without entering the full UI
- Signature carving from binary blobs
- Strings and format-aware forensics helpers (PE/ELF/ZIP/PDF oriented)
- Width and colour controls for terminal presentation

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OHex sample.bin
./OHex sample.bin --hash --entropy
./OHex sample.bin --carve --info
./OHex --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
