<div align="center">

<a href="https://github.com/pandutimurbhaskara">
  <img src="./assets/hero-banner.svg" alt="Pandu Timur Bhaskara — Fullstack & Mobile Engineer" width="100%" />
</a>

<br />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Pandu%20Timur%20Bhaskara-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pandu-timur-b-2aaa6712b/)
[![Email](https://img.shields.io/badge/Email-timurpandu%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:timurpandu@gmail.com)
[![Role](https://img.shields.io/badge/Nanovest-Fullstack%20Engineer-10B981?style=for-the-badge&logo=rocket&logoColor=white)](https://github.com/pandutimurbhaskara)
[![Location](https://img.shields.io/badge/Yogyakarta-Indonesia-F472B6?style=for-the-badge&logo=googlemaps&logoColor=white)](https://github.com/pandutimurbhaskara)

</div>

---

## ⚡ About Me

I'm **Pandu Timur Bhaskara**, a **Fullstack & Mobile Engineer** at **Nanovest** based in **Yogyakarta, Indonesia**. I enjoy building software across the entire stack—from **cross-platform & native mobile apps** (`React Native`, `Flutter`, `SwiftUI`, `Kotlin/Compose`) and **privacy-first on-device AI pipelines** (`ExecuTorch`, `Local LLMs`, `Whisper`, `Kokoro TTS`) to **interactive 3D browser simulations** (`Three.js`, `TypeScript`) and **scalable backend systems** (`Go`, `Java`, `Next.js`).

- 🔭 **Current Focus:** On-device AI inference on mobile devices, native macOS/iOS engineering with Swift 6, and interactive 3D web experiences.
- 🧠 **Engineering Philosophy:** Clean architecture, decoupled simulation/domain cores, zero-latency user interfaces, and local-first privacy.

---

## 🌟 Featured Spotlight Projects

### 1. [CalculatorSwift](https://github.com/pandutimurbhaskara/CalculatorSwift) — Scientific Computation & 2D/3D Graphing Suite

<a href="https://github.com/pandutimurbhaskara/CalculatorSwift">
  <img src="./assets/card-calculator-swift.svg" alt="CalculatorSwift — Scientific Calculator using SwiftUI" width="100%" />
</a>

> **Native macOS 14+ & iOS 17+ scientific calculator and mathematical workspace built from scratch in Swift 6.0 and SwiftUI.**
>
> - **Custom `BigNum` Arithmetic Library:** Arbitrary-precision `BigInt`, `BigDecimal`, exact `Rational` arithmetic, and rational approximations without floating-point drift.
> - **Full Expression Compiler & Engine (`CalculatorCore`):** Custom `Lexer`, recursive-descent `Parser`, symbolic/numeric `Evaluator`, series expansions, physical `Constants`, and dimensional `Units` conversion.
> - **6 Dedicated Interactive Workspaces:**
>   - **Scientific Calculator** (`CalculatorScreen`) · **Linear Algebra & Matrices** (`MatrixWorkspaceView`, `MatrixAlgorithms`)
>   - **Symbolic/Numeric Calculus** (`CalculusWorkspaceView`) · **Statistics** (`StatisticsWorkspaceView`)
>   - **Interactive 2D & 3D Graphing** (`Graph2DView`, `Graph3DView`, `PlotModel`)
>
> 🔗 **[View Repository → `pandutimurbhaskara/CalculatorSwift`](https://github.com/pandutimurbhaskara/CalculatorSwift)**

<br />

### 2. [pastel-tycoon](https://github.com/pandutimurbhaskara/pastel-tycoon) — 3D Browser Transport & Logistics Tycoon

<a href="https://github.com/pandutimurbhaskara/pastel-tycoon">
  <img src="./assets/card-pastel-tycoon.svg" alt="pastel-tycoon — OpenTTD inspired 3D browser game" width="100%" />
</a>

> **An *OpenTTD*-inspired road & rail logistics simulation game in the browser with a soft, low-poly pastel aesthetic inspired by *Package Inc*.**
>
> - **Deep Transport & Signaling Mechanics:** L-shaped procedural curve dragging, rail junctions, one-way block signals, train path reservation (collision-free passing loops), and road/rail depots.
> - **Multi-Tier Supply Chains:** Connect coal mines to power plants or forests to sawmills and growing towns using multi-stop load/unload vehicle schedules.
> - **Decoupled Architecture:** Pure, graphics-independent simulation engine (`src/sim/`) thoroughly tested with **Vitest**, paired with a chunked static-mesh **Three.js** renderer (`src/render/`).
> - **Live Procedural Web Audio Jukebox:** 5 original pastel soundtrack themes synthesized in real time directly in the browser with shuffle, loop, and auto-pause controls.
>
> 🔗 **[View Repository → `pandutimurbhaskara/pastel-tycoon`](https://github.com/pandutimurbhaskara/pastel-tycoon)**

<br />

### 3. [PrivaTalk](https://github.com/pandutimurbhaskara/PrivaTalk) — 100% On-Device AI Suite (LLM, STT & TTS)

<a href="https://github.com/pandutimurbhaskara/PrivaTalk">
  <img src="./assets/card-privatalk.svg" alt="PrivaTalk — Local AI apps (Speech to Text, Text to Speech, LLM) built using React Native" width="100%" />
</a>

> **Privacy-first mobile AI application running Large Language Models, Speech-to-Text, and Text-to-Speech 100% locally on-device using React Native, Expo, and ExecuTorch.**
>
> - **Private On-Device LLM Chat:** Download and run quantized **Llama 3.2 (1B)**, **Qwen3 (0.6B)**, and **SmolLM2 (135M / 360M)** models completely offline with zero cloud API calls.
> - **Offline Speech-to-Text (Whisper):** Transcribe live microphone recordings or direct audio files (`.mp3`, `.wav`, `.m4a`) on-device using quantized & multilingual **Whisper (Tiny / Base / Small)** models.
> - **Offline Text-to-Speech (Kokoro):** Natural neural voice synthesis powered by **Kokoro TTS (Small & Medium)** running directly on mobile hardware.
> - **Local-First Stack:** Built with **Expo SDK 54**, **React Native 0.81**, **`react-native-executorch`**, **`react-native-rag`**, **`op-sqlite`**, **MMKV**, **Zustand**, and bilingual (`EN` / `ID`) localization.
>
> 🔗 **[View Repository → `pandutimurbhaskara/PrivaTalk`](https://github.com/pandutimurbhaskara/PrivaTalk)**

---

## 🗂️ More Projects & Open Source Work

| Project | Domain | Stack | Highlights |
| :--- | :--- | :--- | :--- |
| **[VaultNote](https://github.com/pandutimurbhaskara/VaultNote)** | Local AI Productivity | `TypeScript` `React Native` `Local AI` | Markdown note & expense tracker with local LLM, STT, and on-device image detection |
| **[BrainBooster](https://github.com/pandutimurbhaskara/BrainBooster)** | Mobile Game | `TypeScript` `React Native` `Reanimated` | Math memory and logic puzzle game with fluid 60/120fps animations |
| **[saas-turborepo-template](https://github.com/pandutimurbhaskara/saas-turborepo-template)** | Fullstack Architecture | `TypeScript` `Next.js` `Turborepo` | Monorepo starter for subdomain-isolated SaaS apps with shared auth, UI & data layers |
| **[compose-media-editor](https://github.com/pandutimurbhaskara/compose-media-editor)** | Native Android | `Kotlin` `Jetpack Compose` | Native Android media editing toolkit built with modern Jetpack Compose |
| **[invitasi](https://github.com/pandutimurbhaskara/invitasi)** / **[invitasi-web](https://github.com/pandutimurbhaskara/invitasi-web)** | Fullstack Web & API | `Go` `TypeScript` `React` | Digital invitation platform with a Go backend service and TypeScript web client |

---

## 🛠️ Tech Stack & Toolbox

### Mobile & Native Development
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white)
![Swift](https://img.shields.io/badge/Swift_6-F05138?style=for-the-badge&logo=swift&logoColor=white)
![SwiftUI](https://img.shields.io/badge/SwiftUI-007AFF?style=for-the-badge&logo=swift&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)

### Frontend, 3D & Interactive Web
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=threedotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)

### On-Device AI, Backend & Data
![ExecuTorch](https://img.shields.io/badge/ExecuTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Turborepo](https://img.shields.io/badge/Turborepo-EF4444?style=for-the-badge&logo=turborepo&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)

---

<div align="center">
  <sub>Built & maintained by <b><a href="https://github.com/pandutimurbhaskara">Pandu Timur Bhaskara</a></b> · Yogyakarta, Indonesia 🇮🇩</sub>
</div>
