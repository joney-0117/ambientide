<div align="center">

![](assets/banner.png)

# Ambientide

***"Music companion for your deepest focus."***

An ambient visualizer for your Mac, ebbing and glowing in perfect rhythm with your music.

[📼 See it in action](https://youtu.be/iVROsdQUONQ) | [💻 Download for macOS](https://github.com/sumimakito/ambientide/releases)

</div>

---

Ambientide is a macOS application that transforms your screen edges into a responsive ambient glow. It captures and analyzes system audio in real time to render a smooth, animated, colorful visual tide that hugs the boundaries of every display, including the MacBook notch.

## Features

- **Edge & Notch Glow** — Displays a click-through overlay pinned above all content on every screen, featuring dedicated visual effects tailored for the MacBook notch.
- **Intelligent Tint Modes**
  - **Solid** — Uses a fixed, user-defined color.
  - **Genre** — Classifies audio into one of 13 supergenres and blends a matching color palette accordingly.
  - **Mood** — Maps music onto a color space based on Russell's circumplex model (ranging from calm↔energetic and gloomy↔bright).
- **Real-Time, On-Device Processing** — All audio capture, analysis, and ML inference run strictly locally. No network requests, no tracking, and no accounts required.
- **Highly Customizable** — Fine-tune your experience with per-edge toggles, custom glow modes, animation behaviors, and visual styles.
- **Lightweight Efficiency** — CoreML-accelerated inference leverages the Apple Neural Engine (ANE) whenever possible.

Ambientide is a macOS app that turns your screen edges into an ambient
glow that reacts to whatever is playing. It listens to your system audio, analyzes
it in real time, and renders an animated and colorful glow that hugs the edges of every display, including the notch on your MacBook.

## Requirements

- macOS Sonoma 14.4 or later
- An Apple Silicon Mac is recommended (CoreML inference uses the Neural Engine).

## Permissions

Ambientide captures system audio through a Core Audio process tap, which macOS gates
behind the **system-audio-recording** privacy category. Approve the prompt on first
capture, or enable Ambientide under **System Settings → Privacy & Security → Screen &
System Audio Recording** (labeled **Screen Recording** on macOS Sonoma), for Ambientide
to react to audio.

## Acknowledgments

Ambientide is developed with partial assistance from AI coding companions.