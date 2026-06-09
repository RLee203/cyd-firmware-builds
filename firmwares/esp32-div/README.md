# ESP32-DIV

Custom firmware releases for `ESP32-DIV` across multiple CYD variants.

## Releases

- File: `esp32-div-cyd28-merged.bin`
- Flash address: `0x0`
- Variant: default `CYD 2.8-inch`

- File: `esp32-div-cyd28-v2-merged.bin`
- Flash address: `0x0`
- Variant: alternate `CYD 2.8-inch` layout, including `CYD 2 USB v2`

- File: `esp32-div-cyd-c5-merged.bin`
- Flash address: `0x0`
- Variant: `CYD-C5`

- File: pending
- Flash address: `0x0`
- Variant: `CYD 3.5-inch` placeholder for a future upload

## Board

- Target: `CYD 2.8-inch`, `CYD-C5`, and future `CYD 3.5-inch`
- Variant note: the release files are kept separate per board so each hardware variant can be updated independently
- Pinout reference: [pinout.md](./pinout.md)

## Source

- Source project: private local PlatformIO build
- Built artifacts: merged release binaries generated per supported board

## Notes

- This folder is only for the merged release binary.
- Source code is not included in this repo.
- This release is part of the broader CYD custom firmware collection.
- If the default firmware boots in `landscape`, try `esp32-div-cyd28-v2-merged.bin`.
- The `v2` release should work with `CYD 2 USB v2`.
- `esp32-div-cyd-c5-merged.bin` is the dedicated `CYD-C5` release and should not replace the `CYD 2.8-inch` files.
