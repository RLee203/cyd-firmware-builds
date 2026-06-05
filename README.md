# CYD Custom Firmwares

This repo is a small, organized collection of custom firmware `.bin` files for different CYD variants.

Each firmware gets its own folder with:

- a short firmware README
- one or more merged release binaries
- target board details
- simple flashing info

## Layout

```text
firmwares/
  <firmware-name>/
    README.md
    releases/
      <firmware>-<board>-merged.bin
      <firmware>-<board>-v2-merged.bin

docs/
  flashing.md

firmware-index.md
```

## Current firmwares

- `ESP32-DIV` for `CYD 2.8-inch`

## Current CYD 2.8-inch release files

- `esp32-div-cyd28-merged.bin`
- `esp32-div-cyd28-v2-merged.bin`

If the normal firmware boots in `landscape`, try the `v2` firmware for the alternate 2.8-inch CYD variant.

## Variants

This repo is meant to grow over time with different custom CYD firmwares for different board variants.

## Purpose

This repo is focused on release-ready merged binaries that are easy to share, flash, and organize.
