# LOCK//LINK — SPI-style Digital Lock Portfolio

A responsive, single-page portfolio for a 2-bit SPI-style digital-lock project. Includes Home, Introduction, System Design, an interactive Live Simulator, Results/Verification, and Bill of Materials.

## Run locally

Open `index.html` in a modern browser. No build tools or server are required. Internet is only used for Google Fonts; the page otherwise runs locally.

## Files
- `index.html` — page content and sections
- `style.css` — responsive visual design and animations
- `script.js` — interactive two-bit password/status simulator

## Accuracy notes
- The browser simulator illustrates the intended project logic; it is not connected to Proteus or hardware.
- The design describes a 2-bit password comparison using 74HC165, 74HC595, 74HC85 and 74HC32.
- Validate the real circuit's SH/LD, clock, and ST_CP/latch timing in Proteus before reporting measured results.
- Check the final schematic before treating the BOM quantities as final.
