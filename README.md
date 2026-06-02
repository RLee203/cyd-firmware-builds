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

docs/
  flashing.md

firmware-index.md
```

## Current firmwares

- `ESP32-DIV` for `CYD 2.8-inch`

## Variants

This repo is meant to grow over time with different custom CYD firmwares for different board variants.

## Purpose

This repo is focused on release-ready merged binaries that are easy to share, flash, and organize.
