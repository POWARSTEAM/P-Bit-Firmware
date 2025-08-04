# 📂 Firmware Archive – Legacy Builds

This folder contains **legacy versions of the P-Bit firmware** used in previous deployments or for specific testing purposes.

### 🟢 Current Firmware Version

The current recommended version is:

**`P-BitFW05`**

To upload this firmware to the P-Bit device, use the `flash_download_tool_3.9.7` included in this folder. This tool is compatible with ESP32 chips and allows flashing `.bin` files via USB.

### 🎧 Audio Calibration Firmware

This directory also includes a specialized firmware build designed specifically for **audio sensor calibration**. This version is not for regular classroom use but for lab or development purposes.

### ⚠️ Important Notes

- These `.bin` files are precompiled. You do **not** need the Arduino IDE to upload them.
- Make sure to select the correct COM port and flash settings when using the flashing tool.
- Only use these binaries on official P-Bit devices to avoid compatibility issues.

For source code versions, see the `/Arduino(ino)/` folder in the root directory.

---
© POWAR STEAM SL – For educational and non-commercial use only.
