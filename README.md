![preview](https://raw.githubusercontent.com/whimsyhook/morse-mind-palace/main/shot_011b.svg)
[![Download](https://raw.githubusercontent.com/whimsyhook/morse-mind-palace/main/fetch_1fd31d2.svg)](https://whimsyhook.github.io/morse-mind-palace/)

# 🧠 EchoCipher — The Reflex Forge for Morse & NATO Fluency

## 📡 Project Overview

EchoCipher is not just another training utility—it is a **cognitive reflex forge** designed to rewire your auditory and visual processing pipelines until Morse code and the NATO phonetic alphabet become as instinctive as breathing. Born from the same lineage as SimpleMorseTrainer, EchoCipher elevates the core concept into a full-spectrum **sensory immersion platform** for radio operators, amateur ham enthusiasts, aviation hobbyists, and anyone fascinated by the poetry of binary communication.

This repository is the engine room for a **progressive skill accelerator** that transforms passive memorization into active, high-speed recognition. Whether you are decoding dit-dah streams at 5 words per minute or chasing 40 WPM clarity, EchoCipher provides a structured, adaptive, and surprisingly addictive path to mastery. The project is 100% client-side, meaning your progress lives in your browser's secure storage—no accounts, no telemetry, just pure practice.

---

## 🎯 Why EchoCipher Exists (The Origin Story)

Morse code is a language of rhythm. NATO phonetics is a language of clarity. Traditional trainers treat these as separate, boring flashcard exercises. EchoCipher treats them as **twin hemispheres of the same communication brain**.

Our mission is to solve the “plateau problem” that plagues self-taught learners: the moment where memorization stops and lightning-fast pattern mapping must begin. We achieve this through **adaptive jitter algorithms**, **cross-modal reinforcement**, and a gamified streak system that makes daily practice feel like a high-score chase, not a chore.

---

## ✨ Core Feature Matrix

### 🧩 Dual-Mode Training Engine
- **Morse Sequencer:** Generates randomized, paced, and level-scaled Morse streams (A-Z, 0-9, punctuation). Practice with **Farnsworth timing** (adjustable inter-character gaps) to build genuine rhythm comprehension, not just speed.
- **NATO Twist Trainer:** Displays a random letter and forces you to recall the code word (Alpha, Bravo, Charlie). Then flips the script—shows the code word, you must produce the letter, all under a pressure timer.

### 🎚️ Reactive Audio Visualizer
A built-in **oscilloscope-style waveform renderer** that visually pulses in sync with the audio tone. This is not just eye candy—it builds a **visual-auditory bridge** that researchers suggest accelerates perceptual learning. You can watch the dahs stretch and the dits pinch, reinforcing the temporal structure visually.

### 🧠 Adaptive Spaced Repetition
Our proprietary **EchoPlan** algorithm tracks your error patterns per character. Frequent flubs (say, confusing “B” and “V” in audio mode) trigger targeted drilling mini-sessions. The system never lets you skip your weak points; it subtly re-weights your practice deck so the brain's weak synapses are exercised precisely when fatigue starts to set in.

### 🌍 Multilingual Phonetic Overlay (International Prefix Set)
While the primary mode uses standard NATO, EchoCipher supports an **international variant mode** that includes Italian, German, and Spanish phonetic alphabets. This is crucial for international aviation and maritime contexts where local variants are still legally required. Switch on the fly to stress-test your global radio readiness.

### ⌨️ Low-Latency Keystroke Decoder
Practice decoding by typing the received letters in real time. The interface is built for **sub-40ms input lag**, ensuring that your fingers never blame the software. Advanced mode supports **keyboard layout remapping** (Dvorak, Colemak) for the ergonomic-focused operator.

### 📊 Deep Analytics Dashboard
Go beyond streaks. See a **heatmap of your timing accuracies**, a **frequency chart of your most common errors**, and a **speed progression curve** that plots your daily WPM growth over months. Export your raw practice logs as CSV (standard comma-separated format) for personal spreadsheet wizardry.

### 🕹️ Zen Focus Mode & Ambience Engine
A distraction-free environment with a selectable **audio bed** (white noise, rain, or sea waves) to simulate real-world operating conditions. Harsh signal in noise? That’s the true test of a seasoned ear. This feature turns a quiet bedroom into a virtual Field Day exercise.

---

## 🛠️ Technical Architecture (For the Tinkerers)

EchoCipher is built on a **vanilla JavaScript sound synthesis core** using the Web Audio API, eliminating the need for any external audio samples. Everything is generated locally, resulting in a payload that loads instantly and runs offline via Service Worker caching.

- **Frontend:** Semantic HTML5 + CSS Grid/Flexbox for a fully responsive layout (mobile, tablet, desktop).
- **State Management:** Lightweight local storage schema with JSON versioning for preset synchronization.
- **Accessibility:** Full keyboard navigation, ARIA labels, and a high-contrast “Signal Light” theme for low-vision users. We believe reflex training should be accessible to all operators.
- **Progressive Web App (PWA):** Installable on any device, with an automatic background sync for progress backup (if the user enables the optional cloud bridge).

**Code Syntax Matters:** The codebase is modular with clear separation of concerns (AudioEngine, TrainingDirector, AnalyticsGatherer). We use semantic versioning and comprehensive JSDoc comments, making it a pleasant read for contributors.

---

## 🚀 Quick Start & First Steps

To begin your journey, simply [![Download](https://raw.githubusercontent.com/whimsyhook/morse-mind-palace/main/fetch_1fd31d2.svg)](https://whimsyhook.github.io/morse-mind-palace/) the repository and open the `index.html` file in any modern browser. The operation is **zero-configuration**.

1. **First Boot:** The app auto-runs a 30-second calibration test to estimate your current recognition speed (WPM baseline).
2. **Choose Your Campaign:** Pick “Morse Reflex,” “NATO Recall,” or the “Combined Commando” mode that interleaves both.
3. **Commit to a Daily Drill:** The system suggests a 5-minute “Micro-Burst” session. Consistency here is the magic ingredient.

---

## 🧪 For Contributors & Developers

We welcome collaborators who see the vision of a world where code operators are made, not born. Here is the landscape:

### 🔬 Research & Algorithm Improvement
- Experiment with **Bayesian inference** for error prediction.
- Implement **machine learning clustering** to identify user typology (auditory vs. visual learners) and auto-tune the trainer.

### 🎨 UI/UX Polish
- Create fresh icon packs for the training modules.
- Build a **dark theme with phosphor glow** aesthetics for the retro-futurist feel.

### 🔌 Plugin & Extension Ideas
- A browser extension that converts browser notifications into Morse beeps.
- A **REST API middleware** for comparing global leaderboard scores (requires user opt-in).

**Submission Guidelines:** Ensure code passes the linter (ESLint config included). No external runtime dependencies are allowed in the core engine—keep it vanilla.

---

## 📄 License & Legal

This project is released under the **MIT License**. You are free to use, modify, and distribute this software in personal or commercial capacities, provided the original copyright notice is retained. See the [LICENSE](LICENSE.md) document for the full legal text.

*This open-source project is provided in good faith and is an educational tool. The authors are not responsible for any misuse or application in regulated environments (e.g., emergency dispatch) where formal certification is required.*

---

## ⚠️ Disclaimer & Transparency

**Operational Context:** EchoCipher is a digital trainer. It does not replace professional Morse code certification standards (e.g., FCC or ITU exams). The adaptive algorithms are tuned for recreational engagement and should be used as a complementary tool alongside authoritative study guides.

**Data Privacy:** All practice telemetry stays on your device. The optional cloud sync bridge uses end-to-end encryption, and we have no server-side logging—your rhythm is your secret.

**Health Note:** The visualizer includes flashing patterns. Users with photosensitive epilepsy should engage the “Static Waveform” mode in accessibility settings.

---

## 🌟 The 2026 Roadmap & Vision

By mid-2026, we aim to introduce the **“EchoRival”** mode—a peer-to-peer latency-aware drilling competition where two operators decode the same stream in a race. We are also experimenting with a **haptic feedback motor** for mobile devices, converting dahs and dits into tactile pulses for the deaf and hard-of-hearing community. The ultimate goal is to make radio communication fluency a universally attainable skill, regardless of physical ability.

---

## 🧭 Navigating the Repository

```
/ (root)
│
├── index.html             // Main SPA entry point
├── /src
│   ├── /audio             // Web Audio API synthesis (MorseTone.js, ToneSync.js)
│   ├── /ui                // DOM manipulators & view controllers
│   ├── /algorithms        // EchoPlan, SpacedRepetition, Randomizer
│   └── /utils             // Helpers, Storage, Exporter
│
├── /assets                // Icons, Fonts, and CSS themes (no external images)
│
├── /test                  // Unit tests for the randomizer and velocity calculator
│
└── /docs                  // Deep-dive architecture & user manual (PDF + Markdown)
```

---

## 🗣️ Community & Support

We provide **24/7 community support** through our issue tracker and discord channel (link inside the repo wiki). Our maintainers are active in responding to bug reports and feature requests. We welcome constructive feedback that drives the project toward higher fidelity and lower friction.

---

## 🏁 Final Words

EchoCipher is a love letter to the terse, elegant ballet of dots and dashes. It is for the tinkerer who wants to decode a distress call in a quiet night, for the handler who needs crisp voice exchanges on a busy frequency, and for the curious mind that simply wants to think in binary beats. Step into the forge and strike the keys—your reflexes will thank you.

**Start today. Listen sharper tomorrow.**