# Heltec V2.0 Meshtastic Web Flasher

Flash Meshtastic onto a Heltec WiFi LoRa 32 V2.0 directly from your browser.

## Live Flasher

[Open the web flasher](https://rlee203.github.io/heltec-v2-meshtastic-flasher/)

## Requirements

- Chrome or Edge on desktop
- A data-capable USB cable
- A Heltec WiFi LoRa 32 V2.0

## Important

- This flasher is for `Heltec V2.0` only.
- Do not use this build for `Heltec V2.1` unless a separate V2.1 firmware image is provided.

## How To Use

1. Open the live flasher link above.
2. Plug your Heltec V2.0 into your computer with USB.
3. Click `Connect Board`.
4. Click `Flash Firmware`.
5. Wait for the progress bar and flash log to finish.

## Troubleshooting

- If the browser does not show a serial port, try a different USB cable.
- If the board does not enter flashing mode, hold the boot button while connecting or while flashing starts.
- If the page seems outdated, refresh with `Ctrl+Shift+R`.

## Included Files

- `index.html` - the browser flasher page
- `meshtastic-heltec-v2_0-2.7.23.0cab43f.factory.bin` - the firmware image
- `manifest.json` - the original manifest kept with the project
