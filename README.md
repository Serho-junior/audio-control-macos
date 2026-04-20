# audio-control

> Switch audio devices and control volume per app — all from your menu bar.

<p align="center">
  <a href="https://Serho-junior.github.io/audio-control-macos/">
    <img src="https://img.shields.io/badge/Install-Open%20guide-0071e3?style=for-the-badge&logo=apple&logoColor=white" alt="Install — open installation guide" />
  </a>
</p>

---

## The problem

You want Spotify quieter but Zoom at full volume. You want to switch from AirPods to speakers without opening System Settings. macOS gives you one global volume slider and buries everything else three menus deep.

## What this does

`audio-control` is a menu bar app with two things macOS is missing: per-app volume control and instant audio device switching. One click to switch to AirPods. One slider to turn Spotify down without touching anything else.

- Switch input and output devices with one click
- Separate volume slider for every running app
- AirPods connect and switch automatically
- Keyboard shortcuts for everything

## Menu bar

```
🔊  Click to expand:

  Output device
  ● AirPods Pro          ✓ active
    MacBook Speakers
    Sony WH-1000XM5

  Input device
  ● MacBook Microphone   ✓ active
    AirPods Pro Mic

  ─────────────────────────────
  App volume

  Spotify        ████████░░  80%
  Zoom           ██████████ 100%
  Safari         ████░░░░░░  40%
  Slack          ██████░░░░  60%

  ─────────────────────────────
  [Preferences]
```

## Features

**Device switcher** — all your audio inputs and outputs in one list. Click to switch instantly, no System Settings needed.

**Per-app volume** — independent volume slider for every app that's currently playing or recording audio. Turn Zoom up, Spotify down, mute Slack notifications — without affecting anything else.

**AirPods auto-switch** — detects when AirPods come out of the case and switches to them automatically. Or turn it off and switch manually — your choice.

**Keyboard shortcuts** — assign a shortcut to switch to any device or mute any app. Works system-wide.

**Input control** — switch microphone inputs just as easily as outputs. Useful when you switch between AirPods, a desk mic, and the built-in mic throughout the day.

## Requirements

- macOS 13 Ventura or later
- Apple Silicon or Intel

## Privacy

All audio routing happens locally on your device. No data is collected or transmitted.

## License

MIT
