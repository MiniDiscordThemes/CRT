[screenshot]: https://user-images.githubusercontent.com/29710355/235372934-ff6988b0-daab-41e9-8668-11c8700b80c0.png

[css-color]:        https://developer.mozilla.org/en-US/docs/Web/CSS/color_value
[discord]:          https://discord.gg/uy8nKQVatp

[BetterDiscord]:    https://betterdiscord.app/
[Replugged]:        https://replugged.dev/
[Vencord]:          https://github.com/Vendicated/Vencord

[shield-donate]:    https://img.shields.io/badge/Donate-ko--fi-orange?style=flat-square&logo=kofi&logoColor=orange
[ko-fi]:            https://ko-fi.com/saltssaumure "Buy me a coffee!"

[shield-total-dl]:  https://img.shields.io/github/downloads/MiniDiscordThemes/CRT/CRT.theme.css?color=purple&label=BD%20GitHub%20downloads&style=flat-square
[shield-asar-dl]:   https://img.shields.io/github/downloads/MiniDiscordThemes/CRT/net.saltssaumure.CRT.asar?color=purple&label=Replugged%20downloads&style=flat-square
[shield-repo-size]: https://img.shields.io/github/repo-size/MiniDiscordThemes/CRT?style=flat-square "Total size"

[license]:          https://github.com/MiniDiscordThemes/CRT/blob/main/LICENSE
[issues]:           https://github.com/MiniDiscordThemes/CRT/issues
[.theme.css]:       https://github.com/MiniDiscordThemes/CRT/blob/main/CRT.theme.css

[release-gh]:       https://github.com/MiniDiscordThemes/CRT/releases/latest "Latest GitHub release"
[release-bd]:       https://betterdiscord.app/theme/?id=000 "BetterDiscord store page"
[release-rp-store]: https://replugged.dev/install?identifier=net.saltssaumure.CRT "Replugged store installer"
[release-rp-gh]:    https://replugged.dev/install?identifier=MiniDiscordThemes/CRT&source=github "Replugged GitHub installer"

# CRT Discord Theme
[![Buy me a coffee on ko-fi][shield-donate]][ko-fi]
[![BetterDiscord GitHub downloads][shield-total-dl]][release-gh]
[![Replugged downloads][shield-asar-dl]][release-rp-store]
![Total size][shield-repo-size]

***A CRT monitor effect Discord theme.***

![Screenshot of CRT applied to Discord][screenshot]

## Installation

### BetterDiscord
1. Install [BetterDiscord][BetterDiscord].
2. Download the `CRT.theme.css` file:
    - [GitHub][release-gh]
3. Place theme file in the `themes` folder:
    - Windows: `%AppData%/BetterDiscord/themes`
    - Mac: `~/Library/Application Support/betterdiscord/themes`
    - Linux: `~/.config/BetterDiscord/themes`

### Replugged
1. Install [Replugged][Replugged].
2. Install the theme:
    - [Replugged store][release-rp-store]
    - [GitHub (auto)][release-rp-gh]
    - [GitHub (manual)][release-gh]

### Vencord
1. Install [Vencord][Vencord].
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
3. Copy and paste lines 15-34 of [`CRT.theme.css`](https://github.com/MiniDiscordThemes/CRT/blob/main/CRT.theme.css).
3. Edit the variable values and apply changes.

### Vencord
#### Standard method
1. Follow the instructions in `Settings` > `Vencord` > `Themes`.
#### Recommended method
1. Open `Settings` > `Vencord` > `Vencord`.
2. Toggle on `Enable Custom CSS` and click `Open QuickCSS File`.
3. Copy and paste lines 15-34 of [`CRT.theme.css`](https://github.com/MiniDiscordThemes/CRT/blob/main/CRT.theme.css).
4. Edit the variable values.

## License
[MIT License][license]
- <span title="Too long; didn't read; not a lawyer">TL;DR;NAL</span>: Do whatever you want with this theme, just include the original license.

## Questions or suggestions?
- Post [an issue][issues] on GitHub.
- Post in `#theme-support` on [my support server][discord].
