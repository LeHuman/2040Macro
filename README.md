<!-- PROJECT: PMPi -->
<!-- TITLE: PMPi -->
<!-- FONT: IBM Plex -->
<!-- KEYWORDS: Controller, Raspberry Pi Pico W, Embedded, Hardware, Firmware -->
<!-- LANGUAGES: C, C++, Python -->
<!-- TECHNOLOGY: Mongoose Embedded Web Server, RESTful API, Altium -->
<!-- STATUS: Work In Progress -->

![PMPi-Logo](<images/2040Macro.png>)

[About](#about) - [Key Features](#key-features) - [Related](#related) - [License](#license)

## Status

**`Work In progress`**
> *Still working on the routing - May 2024*

## About
<!-- DESCRIPTION START -->

A macro sized Pico-like board with matching functionality.

This small 'development' board is for Raspberry Pi's RP2040 chip. It aims to match the functionality of Raspberry Pi's Pico development board while responsibly mashing it into the smallest board possible.

<!-- DESCRIPTION END -->

I mention Raspberry Pi a lot, so to clarify, this project is **NOT** involved with or endorsed by Raspberry Pi in anyway.

### Note

As this is simply an experimental prototype, the board has not been tested, nor has it been designed, to be assembled with any commercial processes. The PCB, however, targets JLCPCB's 6 Layer special price of ~$5. This has affected design choices.

### Why

This project has mainly served as an exercise in high density hardware development both in design and manufacturing. This board is mainly meant to be a form of experimentation for myself, hence the choice for the main IO connector.

## Key Features

- Matching Functionality
  - The pinout on the exposed connector matches that of Raspberry Pi's Pico board
  - *Theoretically* any firmware made for the Raspberry Pi's Pico board should work for this board
- Small footprint <!-- TODO: Exact dimensions here -->
- Dual power supply
  - Buck Boost 3.3v switching regulator as main power supply
  - Questionable usage of a linear power supply as an analog reference
- 64M-BIT flash
  - Might affect the matching functionality claim
- Open Source
  - You are reading the open sourcedness of this project

<!-- ## Mechanical -->

<!-- case construction and mounting -->

<!-- ## Electrical -->

<!-- schematics and routing -->

<!-- ## Firmware -->

<!-- programming the Pico W and the Web UI -->

## Related

- [RPDot](https://hackaday.io/project/192519-rpdot)
- [RP2040 Stamp](https://www.solder.party/docs/rp2040-stamp/)
- [Tiny 2040](https://shop.pimoroni.com/products/tiny-2040?variant=39560012234835)
- [XIAO RP2040](https://www.seeedstudio.com/XIAO-RP2040-v1-0-p-5026.html)

## License

MIT
