# 🎹 Piannotation

> **Real-time pitch detection, dynamic polyphonic keyboard mapping, and continuous dual-stave musical notation via the Web MIDI API.**

[🔗 Live Demo](https://<your-username>.github.io/Piannotation/)

---

## 📌 Overview
**Piannotation** bridges physical digital pianos with modern web audio and notation capabilities. By connecting any class-compliant MIDI instrument directly to the browser, Piannotation transcribes live input onto an interactive 88-key visualizer and renders live sheet music across standard Grand Staff (Treble and Bass clefs) in real time.

## ✨ Key Features
- **Zero-Latency MIDI Ingestion:** Direct browser connection via the `Web MIDI API` with automatic port binding and state-change tracking.
- **Polyphonic & Chord Notation:** Groups simultaneous key strikes and renders compound chords dynamically across clefs using `VexFlow`.
- **Continuous Notation Stream:** Real-time horizontal score generation recording played pitches chronologically.
- **Embedded Web Audio Metronome:** High-precision audio metronome with customizable BPM and tempo adjustment.
- **88-Key Responsive Visualizer:** Solfège and pitch-class color mapping with physical press feedback.

## 🛠️ Built With
- **JavaScript (ES6+)**
- **Web MIDI API & Web Audio API**
- **[VexFlow](https://github.com/vexflow/vexflow)** (SVG Sheet Music Rendering Engine)
- **HTML5 & Modern CSS3**

## 🚀 Getting Started
1. Open the [Live Demo](https://<your-username>.github.io/Piannotation/) on a Web MIDI-compatible browser (Google Chrome, Edge, or Android WebViews).
2. Connect your digital piano via USB-MIDI / Bluetooth.
3. Start playing—the application automatically detects incoming MIDI messages and visualizes the notes.