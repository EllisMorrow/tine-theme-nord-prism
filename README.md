<div align="center">

# Nord · Prism

**Snow Storm by day. Polar blue-gray by night. A quiet place for your notes.**

![Modes: light and dark](https://img.shields.io/badge/modes-light%20%2B%20dark-88c0d0?labelColor=2e3440)
![Theme API: 0.2](https://img.shields.io/badge/Tine_theme_API-0.2-88c0d0?labelColor=2e3440)
[![License: MIT](https://img.shields.io/badge/license-MIT-a3be8c?labelColor=2e3440)](LICENSE)
[![Release downloads](https://img.shields.io/github/downloads/EllisMorrow/tine-theme-nord-prism/total?label=release%20downloads&color=88c0d0&labelColor=2e3440)](https://github.com/EllisMorrow/tine-theme-nord-prism/releases)

[Download theme.json](https://github.com/EllisMorrow/tine-theme-nord-prism/releases/latest/download/theme.json) · [中文说明](README.zh-CN.md) · [Adaptation notes](docs/adaptation.md)

</div>

An independent **Nord** palette adaptation for Tine, and the first theme in the **Prism** collection. Both modes have their own complete palette: cool Snow Storm surfaces and blue links in light mode; polar blue-gray surfaces and cyan links in dark mode. Violet tags and amber highlights connect the pair. Typography and layout remain under your control.

### Dark mode

![Nord · Prism in Tine dark mode](docs/nord-dark.png)

*Actual Tine screenshot supplied during Windows testing. The sample graph contains Tine's public welcome content.*

### Light mode

![Nord · Prism in Tine light mode](docs/nord-light.png)

*Actual Windows Tine screenshot of the included light palette. Both modes are part of the same theme package.*

## Install in a minute

1. Download [theme.json](https://github.com/EllisMorrow/tine-theme-nord-prism/releases/latest/download/theme.json).
2. Open **Settings → Appearance → Theme packages → Select theme.json** in Tine.
3. Select the downloaded file, choose **Use colors**, and choose **Light** or **Dark** mode.

Requires support for **Tine Theme API 0.2**. Existing `logseq/custom.css` overrides take priority. A custom device accent may also affect accent/link appearance.

## A small palette, clear roles

| Role | Light | Dark |
| --- | --- | --- |
| Canvas | `#eceff4` | `#2e3440` |
| Sidebar | `#e5e9f0` | `#272c36` |
| Body | `#3b4252` | `#d8dee9` |
| Headings | `#2e3440` | `#d8dee9` |
| Accent | `#355f7c` | `#88c0d0` |
| Links | `#355f7c` | `#b6d9e2` |
| Tags | `#754b76` | `#b48ead` |
| Mark background | `#ead6a4` | Translucent amber |

Each mode supplies all **21 supported color tokens**. Switching modes does not rely on a host fallback palette. The package contains no scripts, custom CSS selectors, fonts, or layout presets. Search, syntax highlighting, task markers and other roles outside the package API remain host-controlled.

## Testing and scope

Version 0.2.0 passed Tine's official theme checker. A Chromium fixture checked both complete token sets and light → dark → light switching; the dark token values remain unchanged from 0.1.1. The user supplied the real Windows screenshots above after installing the dual-mode package. They show headings, body text, outlines, links, tags, inline code, navigation and reference panels. Highlights, text selection, settings-specific states and other platforms are not established by these captures. See [screenshot notes](docs/screenshots.md).

The earlier local CSS prototype included extra component rules. This installable package uses only the public theme API and does not claim to reproduce those unsupported rules. See [adaptation notes](docs/adaptation.md).

## Credits

- **Nord** palette by [Sven Greb / Nord](https://github.com/nordtheme/nord), used under the [MIT license](LICENSE).
- Tine adaptation and Prism packaging by **EllisMorrow**, developed with AI assistance (`aiDevelopment: primary`).
- The dark prototype used the installed Codex Nord preset as a visual reference. The light mode is an original Prism adaptation of Nord Snow Storm / Polar Night colors, with darker blue and violet text for readability; it is not presented as a native Codex light preset. No Codex program code, logo or bundled assets are included.

Independent community theme; no affiliation with or endorsement by Nord or OpenAI. The upstream palette revision is recorded in `theme.json`.

## Feedback

Please [open an issue](https://github.com/EllisMorrow/tine-theme-nord-prism/issues) with your Tine version, operating system, mode and a screenshot without private note content.
