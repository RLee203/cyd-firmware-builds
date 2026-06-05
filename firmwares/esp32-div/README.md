# ESP32-DIV

Custom firmware release for `ESP32-DIV` on the `CYD 2.8-inch` variant.

## Releases

- File: `esp32-div-cyd28-merged.bin`
- Flash address: `0x0`
- Variant: default `CYD 2.8-inch`

- File: `esp32-div-cyd28-v2-merged.bin`
- Flash address: `0x0`
- Variant: alternate `CYD 2.8-inch` layout, including `CYD 2 USB v2`

## Board

- Target: `CYD 2.8-inch`
- Variant note: these releases are for `2.8-inch` CYD models with different hardware variants
- Pinout reference: [pinout.md](./pinout.md)

## Source

- Source project: private local PlatformIO build
- Built artifact: merged CYD 2.8-inch release binary

## Notes

- This folder is only for the merged release binary.
- Source code is not included in this repo.
- This release is part of the broader CYD custom firmware collection.
- If the default firmware boots in `landscape`, try `esp32-div-cyd28-v2-merged.bin`.
- The `v2` release should work with `CYD 2 USB v2`.
