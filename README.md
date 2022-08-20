# SUPERHOT piOS Discord Theme
[![GitHub downloads](https://img.shields.io/github/downloads/saltssaumure/pios-discord-theme/total?color=purple&label=GitHub%20downloads&style=flat-square)](https://github.com/Saltssaumure/pios-discord-theme/releases/latest "Latest release")
![Total size](https://img.shields.io/github/repo-size/saltssaumure/pios-discord-theme?style=flat-square "Total size")

SUPERHOT piOS-inspired theme built for BetterDiscord.

![Screenshot of piOS Discord Theme applied to Discord desktop client](https://user-images.githubusercontent.com/29710355/123527529-72121600-d6d8-11eb-9580-da3987ee8398.png)

## Installation
1. Install [BetterDiscord](https://betterdiscord.app/).
2. Download the theme file:
    - [GitHub](https://github.com/Saltssaumure/pios-discord-theme/releases/latest)
    - [BD Store](https://betterdiscord.app/theme/piOS%20Forever)
3. Place theme file in BD's theme folder:
    - Windows: `%appdata%/betterdiscord/themes`
    - Mac: `~/Library/Application Support/betterdiscord/themes`
    - Linux: `~/.config/BetterDiscord/themes`

## Customisation

### Message display
Cosy mode uses regular Discord layout, while Compact mode has piOS-style boxes.

- **Discord setting:** `User Settings > App Settings > Appearance > Message Display`.

|Cosy|Compact|
|-|-|
|![Cosy](https://user-images.githubusercontent.com/29710355/154400330-eb4434ac-1716-4c3f-bca1-8b6ba509e9c3.png)|![Compact](https://user-images.githubusercontent.com/29710355/154400528-66fea4d8-53c1-4178-91f5-88729bde0e81.png)|

### Glow intensity
Brightness of text glow and status indicator glow. 

- **Theme setting:** change value of `--glow-intensity` to a number between 0 and 1.
- **Default value:** `1` (100% brightness).

| 1 (full glow) | 0 (no glow) |
|-|-|
| ![image](https://user-images.githubusercontent.com/29710355/165006236-eeddba57-b7d6-4bd6-81af-1f649c5000dc.png) ![image](https://user-images.githubusercontent.com/29710355/165006394-3f6b4379-a35f-4506-a855-6a86d9e1f142.png) | ![image](https://user-images.githubusercontent.com/29710355/165006329-896ad462-f94d-447a-acd6-75cb0573cae4.png) ![image](https://user-images.githubusercontent.com/29710355/165006379-8c60fedd-7f42-4f70-a134-33da1a5211e4.png)

### Compact message spacing
Affects spacing between messages in Compact mode (see above).

- **Theme setting:** change value of `--compact-message-spacing` to any positive or zero number.
- **Default value:** `1` (100% of default spacing).

|1 (default)|2.5|
|-|-|
|![Messages are relatively close together.](https://user-images.githubusercontent.com/29710355/162553148-11c5bf02-7b9d-4d46-a8b6-bba509759452.png)|![Spacing between messages is much increased.](https://user-images.githubusercontent.com/29710355/162553169-ef3c2230-5527-4736-9c7f-a4ef1d1f51f1.png)

### Colour accents
Affects colour scheme used throughout the theme.

- **Theme setting:** change value of `--accent-color` to any number. Use a HSL colour picker (eg. [React Color](https://casesandberg.github.io/react-color/)) and copy the H value.
- **Default value:** `0` (red).

|Color picker|Result|
|-|-|
|![Purple in a colour picker with its H value 270 selected.](https://user-images.githubusercontent.com/29710355/162552090-57011aeb-8b97-45e6-a96c-d13287761cf8.png)|![Screenshot of piOS Discord Theme where all colour accents are purple.](https://user-images.githubusercontent.com/29710355/162551985-ed568020-7f12-4300-ad31-0c5a66be4645.png)|

### CRT overlay
Adds CRT monitor style overlay to the whole window.

- **Theme settings:** change value(s) of `--crt-overlay`, `--crt-scanline`, `--crt-flicker`.
- **Values:** `block`/`none`, `block`/`none`, `flicker`/`none`.

![Screenshot of piOS Discord Theme with CRT overlay enabled.](https://user-images.githubusercontent.com/29710355/182611054-c0cb9122-1eac-42ec-93d1-ab5a203a7e15.png)

[Video demonstration of animated scanline](https://drive.google.com/uc?id=1xFbTWA5qIZAurVJdjOptnCd6OMBLBfEz)

### Customisable title text
Adds customisable title text to replace the Discord logo.

- **Theme setting:** change value of `--title-text` to any text in quotations.
- **Default value:** `"piOS v2.1.01p"`.

![image](https://user-images.githubusercontent.com/29710355/185759617-42fc6937-4523-4559-ba9c-5e9bb2ba8d3c.png)


## License
[GNU General Public License v3.0](https://github.com/Saltssaumure/pios-discord-theme/blob/master/LICENSE.md)  
TL;DR: Do what you want with this theme, as long as you also let others do what they want with your version.

## Questions or suggestions?
- Post [an issue](https://github.com/Saltssaumure/pios-discord-theme/issues) on GitHub.
- Post in `#theme-support` on [my support server](https://discord.gg/uy8nKQVatp).
- Ping me on the [SUPERHOT Official server](https://discord.gg/9eAwJF8).
