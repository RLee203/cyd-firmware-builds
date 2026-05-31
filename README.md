# CYD Firmware Builds

This repo is a small, organized collection of merged firmware `.bin` files for CYD board variants.

Each firmware gets its own folder with:

- a short firmware README
- one or more merged release binaries
- target board details
- the source project path or upstream reference

## Layout

```text
firmwares/
  <firmware-name>/
    README.md
    releases/
      <firmware>-<board>-merged.bin

docs/
  flashing.md

firmware-index.md
```

## Current firmware

- `ESP32-DIV` for `CYD 2.8-inch`

## Variant note

The current release in this repo is for the `CYD 2.8-inch` variant.

More CYD variants can be added later in their own firmware folders or release entries as this repo grows.

## Purpose

This repo is focused on release-ready merged binaries, not full source trees.
