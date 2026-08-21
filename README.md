# 🤖 IoT & Embedded Firmware Security Analysis Pipeline

[![GitHub release (latest by date)](https://img.shields.io/github/v/release/toprakahmetaydogmus/17-iot-firmware-emulation?color=blue&label=Release)](https://github.com/toprakahmetaydogmus/17-iot-firmware-emulation/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

Developer: **Toprak Ahmet Aydoğmuş**

---

## 🎯 1. Overview
Embedded Linux and IoT firmware static audit pipeline. Analyzes extracted SquashFS/CramFS root filesystems for hardcoded private keys, default credentials, dangerous setuid binaries, insecure listening daemons, and outdated libraries.

---

## 🚀 2. Quick Start

```bash
git clone https://github.com/toprakahmetaydogmus/17-iot-firmware-emulation.git
cd 17-iot-firmware-emulation
python -m unittest discover tests/
```

---

## 📜 3. License
Licensed under the [MIT License](LICENSE).  
Developer: **Toprak Ahmet Aydoğmuş**.
