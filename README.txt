Heltec V2 Meshtastic custom web flasher

Files in this folder:
- index.html: custom browser flasher with fixed 115200 baud, progress bar, and live flash log
- manifest.json: original esp-web-tools manifest kept for reference
- meshtastic-heltec-v2_0-2.7.23.0cab43f.factory.bin: prebuilt firmware

How to use locally:
1. Serve this folder over http://localhost or HTTPS.
2. Open the page in Chrome or Edge.
3. Click Connect Board.
4. Click Flash Firmware.

Notes:
- This page uses a fixed 115200 baud rate because it is the most reliable option across boards and cables.
- This page is for Heltec V2.0, not V2.1.
- The flasher uses esptool-js from a CDN, so internet access is needed unless you host that script locally.
