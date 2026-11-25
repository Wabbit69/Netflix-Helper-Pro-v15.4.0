# 🎬 Netflix Helper Pro+

A userscript that adds playback controls, picture and audio tweaks, subtitle tools and diagnostics to Netflix in a draggable control panel.

## Features

**Playback**
- Speed control from 0.25x to 3x
- Zoom and crop presets, with automatic black-bar detection
- Mini player (Picture-in-Picture), screenshots and sleep timer
- Optional double-click seeking on the left and right sides of the video

**Picture and audio**
- Shadow lift, sharpness, colour temperature, brightness, contrast and saturation, with presets
- Volume boost up to 300%
- Dialogue Clarity, Night Mode and Cinema Bass audio presets

**Subtitles**
- Size, position and background options
- Replay or copy the current line

**Automation and browsing**
- Skip intros and recaps, play the next episode and dismiss "Are you still watching?"
- Blur episode thumbnails and synopses to avoid spoilers
- Mute autoplay previews
- Links to IMDb, Rotten Tomatoes, Letterboxd and MyAnimeList on title popups, with TVmaze and MyAnimeList scores when a match is found
- Shortcuts to hidden Netflix categories

**Stream tools and diagnostics**
- Live resolution, frame rate, network, buffer and dropped-frame stats
- Player info, player log, stream selector and local `.dfxp` subtitle loading
- Option to prefer the highest bitrate offered to your session
- DRM and format support badges
- Optional diagnostic log blocking and Edge fullscreen fix
- Local watch-time statistics

## Installation

1. Install a userscript manager such as [Tampermonkey](https://www.tampermonkey.net/).
2. Install the script from [Greasy Fork](https://greasyfork.org/scripts/567750), or create a new script in your manager and paste in the `.user.js` file.
3. Open or refresh Netflix.

## Keyboard shortcuts

| Action | Key |
|---|---|
| Show or hide panel | `F2` |
| Replay subtitle line | `R` |
| Copy subtitle line | `Shift` + `X` |
| Mini player | `P` |
| Cycle zoom | `Z` |
| Slower / faster / normal speed | `[` / `]` / `\` |
| Seek 30 seconds | `Shift` + `←` / `→` |
| Volume boost | `Shift` + `↑` / `↓` |
| Hide or show subtitles | `Shift` + `C` |
| Screenshot | `Shift` + `S` |
| Cycle sleep timer | `Shift` + `T` |

## Limitations

- The script does not bypass DRM, plan limits or household restrictions. Resolution depends on what Netflix offers to your browser, device and plan.
- Player tools rely on Netflix internals, so some may stop working after Netflix updates its player.
- Some browsers capture DRM-protected video as a blank frame, so screenshots may not work.

## Privacy

Settings and watch statistics are saved in your userscript manager. When title ratings are enabled, title names are sent to [TVmaze](https://www.tvmaze.com/) and [Jikan](https://jikan.moe/) to look up scores.

## Disclaimer

This is an unofficial project and is not affiliated with or endorsed by Netflix.

## License

MIT © Wabbit
