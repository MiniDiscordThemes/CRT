[screenshot]: https://user-images.githubusercontent.com/29710355/235372934-ff6988b0-daab-41e9-8668-11c8700b80c0.png

# CRT Discord Theme
[![GitHub downloads](https://img.shields.io/github/downloads/MiniDiscordThemes/CRT/total?color=purple&label=GitHub%20downloads&style=flat-square)](https://github.com/MiniDiscordThemes/CRT/releases/latest "Latest release")
![Total size](https://img.shields.io/github/repo-size/MiniDiscordThemes/CRT?style=flat-square "Total size")

***A CRT monitor effect Discord theme.***

![Screenshot of CRT applied to Discord][screenshot]

## Installation

### BetterDiscord
1. Install [BetterDiscord](https://betterdiscord.app/).
2. Download the theme file:
    - [GitHub](https://github.com/MiniDiscordThemes/CRT/releases/latest)
3. Place theme file in the `themes` folder:
    - Windows: `%AppData%/BetterDiscord/themes`
    - Mac: `~/Library/Application Support/betterdiscord/themes`
    - Linux: `~/.config/BetterDiscord/themes`

### Replugged
1. Install [Replugged](https://replugged.dev/).
2. Install the theme:
    - [GitHub](https://github.com/MiniDiscordThemes/CRT/releases/latest)
    - [Replugged.dev](https://replugged.dev/install?identifier=MiniDiscordThemes/CRT&source=github)

### Vencord
1. Install [Vencord](https://github.com/Vendicated/Vencord).
2. Paste the following in `Settings` > `Vencord` > `Themes`:
    - `https://minidiscordthemes.github.io/CRT/CRT.theme.css`

## Customisation

| Description                    | Variable name                                         | Valid values                                        | Default value                                    |
| ------------------------------ | ----------------------------------------------------- | --------------------------------------------------- | ------------------------------------------------ |
| Stacking position              | `--crt-height`                                        | Any number.                                         | `9999`                                           |
| Size of scanlines              | `--crt-size`                                          | Any length, preferrably in `px`.                    | `4px`                                            |
| Scanline stripes on/off        | `--crt-stripe`                                        | `block` (on) or `none` (off).                       | `block`                                          |
| Scanline stripes colour        | `--crt-stripe-light-color`, `--crt-stripe-dark-color` | Any CSS-recognised colour, low opacity recommended. | `rgba(255, 255, 255, 0.1)`, `rgba(0, 0, 0, 0.1)` |
| &#9936; Moving scanline on/off | `--crt-scanline`                                      | `block` (on) or `none` (off).                       | `block`                                          |
| Moving scanline speed          | `--crt-scanline-speed`                                | Any time, in `ms` or `s`.                           | `3s`                                             |
| Moving scanline colour         | `--crt-scanline-color`                                | Any CSS-recognised colour.                          | `rgba(0, 0, 0, 0.5)`                             |
| Moving scanline direction      | `--crt-scanline-direction`                            | `normal` or `reversed`.                             | `normal`                                         |
| &#9888; Screen flicker on/off  | `--crt-flicker`                                       | `flicker` (on) or `none` (off).                     | `none`                                           |
| Screen flicker speed           | `--crt-flicker-speed`                                 | Any time, in `ms` or `s`                            | `calc(1s/30)`                                    |
| Screen flicker colour          | `--crt-flicker-color`                                 | Any CSS-recognised colour, low opacity recommended. | `rgba(0, 0, 0, 0.1)`                             |

- &#9936; This effect is performance-intensive.
- &#9888; This is a fast flickering effect and may not be suitable for those with photosensitive epilepsy.


### BetterDiscord
1. Open `Settings` > `BetterDiscord` > `Themes`.
2. Click the pencil icon on this theme.
3. Edit the variable values and save changes.

### Replugged
1. Open `Settings` > `Replugged` > `Quick CSS`.
3. Copy and paste lines 16-34 of [`CRT.theme.css`](https://github.com/MiniDiscordThemes/CRT/blob/main/CRT.theme.css).
3. Edit the variable values and apply changes.

### Vencord
#### Standard method
1. Follow the instructions in `Settings` > `Vencord` > `Themes`.
#### Recommended method
1. Open `Settings` > `Vencord` > `Vencord`.
2. Toggle on `Enable Custom CSS` and click `Open QuickCSS File`.
3. Copy and paste lines 16-34 of [`CRT.theme.css`](https://github.com/MiniDiscordThemes/CRT/blob/main/CRT.theme.css).
4. Edit the variable values.

## License
[MIT License](https://github.com/MiniDiscordThemes/CRT/blob/main/LICENSE)
- <span title="Too long; didn't read; not a lawyer">TL;DR;NAL</span>: Do whatever you want with this theme, just include the original license.

## Questions or suggestions?
- Post [an issue](https://github.com/MiniDiscordThemes/CRT/issues) on GitHub.
- Post in `#theme-support` on [my support server](https://discord.gg/uy8nKQVatp).
