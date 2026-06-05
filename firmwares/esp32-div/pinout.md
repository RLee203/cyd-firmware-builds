# ESP32-DIV CYD 2.8 Pinout

This document summarizes the pin mapping used by the `ESP32-DIV` firmware for the `CYD 2.8-inch` target.

The values below are based on the `CYD_28` board overrides in the source configuration.

## Display

Display type: `ILI9341`

The source comments describe the display wiring like this:

- `MOSI`: `GPIO13`
- `MISO`: `GPIO12`
- `SCLK`: `GPIO14`
- `CS`: `GPIO15`
- `DC`: `GPIO2`
- `Backlight`: `GPIO21`

## Touch

Touch controller: `XPT2046`

- `CS`: `GPIO33`
- `MOSI`: `GPIO32`
- `MISO`: `GPIO39`
- `CLK`: `GPIO25`

Default touch calibration values in firmware:

- `TOUCH_X_MIN`: `3900`
- `TOUCH_X_MAX`: `200`
- `TOUCH_Y_MIN`: `3850`
- `TOUCH_Y_MAX`: `330`

## SD Card

- `CS`: `GPIO5`
- `MOSI`: `GPIO23`
- `MISO`: `GPIO19`
- `SCLK`: `GPIO18`
- `Card detect`: `GPIO38`

## Backlight

- `Backlight`: `GPIO21`

## Battery

- `Battery ADC`: `GPIO34`
- Divider note: firmware uses `100k / 100k` for the CYD 2.8 board profile

## GPS

- `RX`: `GPIO3`
- `TX`: `GPIO1`

## CC1101

- `SCK`: `GPIO18`
- `MISO`: `GPIO19`
- `MOSI`: `GPIO23`
- `CS`: `GPIO27`
- `GDO0 / TX pin`: `GPIO22`
- `GDO2 / RX pin`: `GPIO35`

## PN532

- `SCK`: `GPIO18`
- `MISO`: `GPIO19`
- `MOSI`: `GPIO23`
- `SS`: `GPIO17`

## NRF24

- `CE`: `GPIO16`
- `CSN`: `GPIO4`

Only the first NRF24 mapping is used for `CYD_28` in the current source profile.

## IR

For the `CYD_28` profile in the current source:

- `IR_TX_PIN`: disabled (`-1`)
- `IR_RX_PIN`: disabled (`-1`)

## Notes

- If the normal firmware boots in `landscape`, try the `v2` firmware release.
- The `v2` release should work with `CYD 2 USB v2`.
- This page is documentation for the firmware pin mapping, not a guarantee for every third-party CYD clone.
