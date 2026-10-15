# 🎹 Piannotation

> **Real-time pitch detection, dynamic polyphonic keyboard mapping, and dual-stave musical notation via the Web MIDI API & Web Audio API.**

[🔗 Live Demo](https://m-m1.github.io/Piannotation/)

---

## 📌 Overview
**Piannotation** bridges physical digital pianos with modern web audio and interactive notation capabilities. By connecting any class-compliant MIDI instrument directly to the browser—or utilizing the integrated virtual piano—Piannotation transcribes live input onto an interactive 88-key visualizer and renders sheet music across standard Grand Staff (Treble and Bass clefs) in real time.

## ✨ Key Features
- **Zero-Latency MIDI Ingestion:** Direct hardware connection via the `Web MIDI API` with automatic device detection and state-change tracking.
- **Interactive Virtual Keyboard & QWERTY Input:** Play directly on-screen with mouse/touch or use computer keyboard keys (`A`–`K`) with zero configuration.
- **Acoustic Piano Synthesizer:** Built-in multi-oscillator Web Audio engine with harmonic layering, dynamic low-pass filtering, and realistic acoustic release envelopes.
- **Dual Middle Octaves (C3–C5):** Optional toggle to display central pitches simultaneously on both Treble and Bass staves with dynamic ledger lines.
- **Dual Display Modes:**
  - **Single Stave Mode:** Focuses cleanly on the most recent chord or note voicing, persisting until the next strike.
  - **Stream Mode:** Records continuous horizontal notation history with an integrated reset control.
- **Embedded Web Audio Metronome:** High-precision audio metronome with customizable BPM and tempo controls.
- **Persistent Visualizer:** 88-key visual feedback displaying pitch classes, Solfège labeling, and color-coded key depressions that persist until new input is received.

## 🛠️ Built With
- **JavaScript (ES6+)**
- **Web MIDI API & Web Audio API**
- **[VexFlow](https://github.com/vexflow/vexflow)** (SVG Sheet Music Rendering Engine)
- **HTML5 & Modern CSS3**

## 🚀 Getting Started
1. Open the [Live Demo](https://m-m1.github.io/Piannotation/) on any modern browser (Chrome, Edge, or Android WebViews recommended for Web MIDI).
2. Connect your digital piano via USB-MIDI / Bluetooth, or simply use the on-screen virtual keyboard / computer keys.
3. Toggle between **Single** or **Stream** view and start playing!