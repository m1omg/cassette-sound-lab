# Cassette Sound Lab

A local, browser-based cassette-tape reproduction simulator. Load an audio file and hear it through a Web Audio "tape" chain — transport wow & flutter, tape hiss, soft saturation, band limiting, head bump, azimuth error, channel crosstalk, dropouts, and mains hum.

Everything runs locally in your browser. Your audio file never leaves your device.

## Live demo

**https://m1omg.github.io/cassette-sound-lab/**

## Features

- Plays MP3 / WAV / OGG / M4A via the browser audio engine (handles long files without decoding everything into RAM)
- Optional cassette artifacts, each individually adjustable:
  - Wow & flutter (transport speed variation)
  - Tape hiss / noise
  - Soft tape saturation
  - Limited bandwidth
  - Head bump
  - Azimuth error
  - Channel crosstalk
  - Dropouts
  - Mains hum
- Bypass FX toggle for A/B comparison
- Slovak / English UI
- Mobile-friendly responsive layout

## Usage

Just open the live demo, or download and open `index.html` in any modern browser. No build step, no server, no dependencies.

## License

MIT
