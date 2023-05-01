[screenshot-old]: https://user-images.githubusercontent.com/29710355/123527529-72121600-d6d8-11eb-9580-da3987ee8398.png
[screenshot]: https://user-images.githubusercontent.com/29710355/235468134-a4f95a88-627a-4ed9-ae3d-b288591374b2.png

[cosy]: https://user-images.githubusercontent.com/29710355/154400330-eb4434ac-1716-4c3f-bca1-8b6ba509e9c3.png
[compact]: https://user-images.githubusercontent.com/29710355/154400528-66fea4d8-53c1-4178-91f5-88729bde0e81.png

[glow-1a]: https://user-images.githubusercontent.com/29710355/165006236-eeddba57-b7d6-4bd6-81af-1f649c5000dc.png
[glow-1b]: https://user-images.githubusercontent.com/29710355/165006394-3f6b4379-a35f-4506-a855-6a86d9e1f142.png
[glow-0a]: https://user-images.githubusercontent.com/29710355/165006329-896ad462-f94d-447a-acd6-75cb0573cae4.png
[glow-0b]: https://user-images.githubusercontent.com/29710355/165006379-8c60fedd-7f42-4f70-a134-33da1a5211e4.png

[spacing-1]: https://user-images.githubusercontent.com/29710355/162553148-11c5bf02-7b9d-4d46-a8b6-bba509759452.png
[spacing-2.5]: https://user-images.githubusercontent.com/29710355/162553169-ef3c2230-5527-4736-9c7f-a4ef1d1f51f1.png

[hue-picker]: https://user-images.githubusercontent.com/29710355/162552090-57011aeb-8b97-45e6-a96c-d13287761cf8.png
[hue-screenshot]: https://user-images.githubusercontent.com/29710355/162551985-ed568020-7f12-4300-ad31-0c5a66be4645.png

[title-text]: https://user-images.githubusercontent.com/29710355/185759617-42fc6937-4523-4559-ba9c-5e9bb2ba8d3c.png

[crt-stripe]: https://user-images.githubusercontent.com/29710355/182611054-c0cb9122-1eac-42ec-93d1-ab5a203a7e15.png
[crt-scanline]: https://drive.google.com/uc?id=1xFbTWA5qIZAurVJdjOptnCd6OMBLBfEz

# piOS Discord Theme
[![GitHub downloads](https://img.shields.io/github/downloads/saltssaumure/pios-discord-theme/total?color=purple&label=GitHub%20downloads&style=flat-square)](https://github.com/Saltssaumure/pios-discord-theme/releases/latest "Latest release")
![Total size](https://img.shields.io/github/repo-size/saltssaumure/pios-discord-theme?style=flat-square "Total size")

***A SUPERHOT piOS inspired Discord theme.***

![Screenshot of piOS Discord Theme applied to Discord desktop client][screenshot]

## Installation

### BetterDiscord
1. Install [BetterDiscord](https://betterdiscord.app/).
2. Download the theme file:
    - [GitHub](https://github.com/Saltssaumure/pios-discord-theme/releases/latest)
    - [BD Store](https://betterdiscord.app/theme/?id=572)
3. Place theme file in BD's theme folder:
    - Windows: `%AppData%/BetterDiscord/themes`
    - Mac: `~/Library/Application Support/betterdiscord/themes`
    - Linux: `~/.config/BetterDiscord/themes`

### Replugged
1. Install [Replugged](https://replugged.dev/).
2. Install the theme:
    - [GitHub](https://github.com/Saltssaumure/pios-discord-theme/releases/latest)
    - [Replugged.dev](https://replugged.dev/install?identifier=Saltssaumure/pios-discord-theme&source=github)

### Vencord
1. Install [Vencord](https://github.com/Vendicated/Vencord).
2. Paste the following in `Settings` > `Vencord` > `Themes`:
    - `https://saltssaumure.github.io/pios-discord-theme/piOS.theme.css`

## Customisation

- **Discord setting:** `Settings` > `App Settings` > `Appearance` > `Message Display`.

| Cosy          | Compact             |
| ------------- | ------------------- |
| ![Cosy][cosy] | ![Compact][compact] |

| Description                    | Variable name           | Valid values                    | Default value            | Demonstration                                                               |
| ------------------------------ | ----------------------- | ------------------------------- | ------------------------ | --------------------------------------------------------------------------- |
| Glow intensity                 | `--pios-glow-intensity` | A number between `0` and `1`.   | `1` (maximum brightness) | `1` [chat][glow-1a], [icon][glow-1b] / `0` [chat][glow-0a], [icon][glow-0b] |
| Compact message spacing        | `--pios-spacing`        | A number `0` or above.          | `1` (default spacing)    | [`1` spacing][spacing-1] / [`2.5` spacing][spacing-2.5]                     |
| Colour accent hue              | `--pios-accent-hue`     | Any number.                     | `0` (red)                | `270` (purple) [colour picker][hue-picker], [screenshot][hue-screenshot]    |
| Title bar text                 | `--pios-title-text`     | Any quoted text.                | `"piOS v2.1.01p"`        | [Screenshot][title-text]                                                    |
| Scanline stripes on/off        | `--crt-stripe`          | `block` (on) or `none` (off).   | `block`                  | [Screenshot][crt-stripe]                                                    |
| &#9936; Moving scanline on/off | `--crt-scanline`        | `block` (on) or `none` (off).   | `block`                  | [Video][crt-scanline]                                                       |
| &#9888; Screen flicker on/off  | `--crt-flicker`         | `flicker` (on) or `none` (off). | `none`                   |

- &#9936; This effect is performance-intensive.
- &#9888; This is a fast flickering effect and may not be suitable for those with photosensitive epilepsy.

### BetterDiscord
1. Open `Settings` > `BetterDiscord` > `Themes`.
2. Click the pencil icon on this theme.
3. Edit the variable values and save changes.

### Replugged
1. Open `Settings` > `Replugged` > `Quick CSS`.
3. Copy and paste line 15-25 of [`piOS.theme.css`](https://github.com/Saltssaumure/pios-discord-theme/blob/main/piOS.theme.css).
3. Edit the variable values and apply changes.

### Vencord
#### Standard method
1. Follow the instructions in `Settings` > `Vencord` > `Themes`.
#### Recommended method
1. Open `Settings` > `Vencord` > `Vencord`.
2. Toggle on `Enable Custom CSS` and click `Open QuickCSS File`.
3. Copy and paste line 15-25 of [`piOS.theme.css`](https://github.com/Saltssaumure/pios-discord-theme/blob/main/piOS.theme.css).
4. Edit the variable values.

## License
[GNU General Public License v3.0](https://github.com/Saltssaumure/pios-discord-theme/blob/main/LICENSE)
- <span title="Too long; didn't read; not a lawyer">TL;DR;NAL</span>: Do whatever you want with this theme, as long as you allow others to do the same with your version.

## Questions or suggestions?
- Post [an issue](https://github.com/Saltssaumure/pios-discord-theme/issues) on GitHub.
- Post in `#theme-support` on [my support server](https://discord.gg/uy8nKQVatp).
