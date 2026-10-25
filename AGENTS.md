# embedded

Firmware for microcontrollers, one repository each, as siblings of `project`.

- The hardware is a Raspberry Pi Pico W (RP2040 + CYW43439) with a Waveshare 5.83" e-paper V2 (648x480, black and white) on the Pico-ePaper board.
- The Pico stays near the Mac, on its USB or on its own power, so firmware work happens on the Mac.
- It is on the Wi-Fi `7g` as `inkpico.local`.
- Each repository has the Pico SDK in its flake's dev shell.
- Prose in these repositories, AGENTS.md included, needs no acceptance as a diff.

## Repositories

Each entry is the directory, then the repository it checks out.

- `project` (`embedded-project`): this file and the `mani.yaml`, public
- `pico-ota` (`pico-ota`): the Wi-Fi bootloader and the runtime every app links, public
- `inkpico` (`inkpico`): the e-paper display, as apps on `pico-ota`, public
