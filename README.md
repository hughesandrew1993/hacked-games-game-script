# HACKED GAMES v - Game Script Utility 2026

> A browser-first platformer built from corruption, glitches, and concealed inputs. Made for web play, it combines canvas rendering, HTML5 structure, JavaScript behavior, and WebAudio to deliver a reactive game flow.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/hughesandrew1993/hacked-games-game-script?style=flat-square)](https://github.com/hughesandrew1993/hacked-games-game-script)

---

<p align="center">
  <a href="https://hughesandrew1993.github.io/hacked-games-game-script/">
    <img src="https://img.shields.io/badge/Download-HACKED%20GAMES%20Script-brightgreen?style=for-the-badge" alt="Download HACKED GAMES Script">
  </a>
</p>

> **[Direct Download - HACKED GAMES](https://hughesandrew1993.github.io/hacked-games-game-script/)**

---

[Download Latest Build](https://hughesandrew1993.github.io/hacked-games-game-script/)

---

## Project Summary

HACKED GAMES is a web platformer built around deliberate glitches, corruption, and mechanics that bend the rules as you progress. It runs on the standard browser game stack of canvas, JavaScript, HTML5, and WebAudio, creating a play experience that becomes increasingly distorted over time.

Along the way, the game presents a hidden terminal, a staged crash event, and a corruption meter that reflects your run state. Input is available through both keyboard and touch controls, and progress is retained through localStorage between sessions.

## Script Features

- Intentional glitch-driven gameplay effects
- Rule corruption that alters how the game responds
- Wall and platform phasing mechanics
- Hidden terminal interface for in-game access
- Fake system crash sequence as part of the experience
- Corruption progression meter for tracking state changes
- Touch and keyboard control support
- localStorage save support for browser sessions

## Setup

1. Open the project in a web server or browser-compatible local preview.
2. Load the main HTML entry point in a modern browser.
3. Use keyboard or touch controls to begin play.
4. If you want to keep progress, allow the browser to store local save data.

Minimal launch example:

- Open the HTML5 entry file in your browser
- Or serve the folder locally and load it from `localhost`

## Options

This game does not provide a broad external configuration layer, but the following in-game behaviors matter during play:

| Setting | Purpose |
| --- | --- |
| Keyboard input | Move and interact from desktop browsers |
| Touch input | Play on supported mobile or touch devices |
| Corruption meter | Shows progression through the glitch state |
| Save storage | Keeps data in localStorage between sessions |
| Terminal access | Reveals hidden interface elements during play |

## Compatibility

HACKED GAMES is intended for browser-based play on the web. Its source profile indicates HTML, JavaScript, canvas, and WebAudio usage, so a modern browser is the main requirement.

Known considerations:

- Best suited to current desktop and mobile browsers
- Touch support is included, but behavior may differ by device
- localStorage must be available for save persistence
- Visual effects such as CRT-style shading may vary with browser rendering

## FAQ

### How do I start playing?
Open the project in a browser and launch the main HTML entry point. If you are hosting it locally, use a local web server for the smoothest result.

### Does it support mobile devices?
Yes. The profile includes touch controls, so the game can be used on supported touch-enabled browsers.

### How are updates handled?
Updates generally focus on browser gameplay behavior, corruption mechanics, and the hidden interface rather than external tooling.

### Can I customize the experience?
Customization depends on the source files and how the game is packaged. Any changes should be made in the project assets and scripts.

### Where is save data stored?
Save progress uses localStorage in the browser, so data is tied to the browser profile and the device environment.

### What should I do if the display looks unusual?
The game intentionally uses glitch and corruption effects. If visuals appear broken beyond the intended design, try another modern browser or refresh the session.

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
