# Changelog

## 0.1.1

- Support Foundry VTT v13 alongside v14 (`compatibility.minimum` lowered from `14` to `13`; verified against 13.351 and 14.359).
- Position the DC tracker and PC display against the scene navigation by measuring its orientation rather than assuming a horizontal bar. v14 draws the nav as a horizontal bar across the top; v13 draws it as a vertical column down the left side, where hanging off the bottom edge pushed the widgets off-screen.
- Point `manifest` and `download` at this fork so the system installs and updates independently.

## 0.1.0

- Initial release.
