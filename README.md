# Dmytro Babych &mdash; Portfolio & Engineering Deployments

Personal portfolio website and directory of live production projects, cloud micro-frontends, real-time telemetry systems, and interactive WebGL / Canvas engines.

🌐 **Live Portfolio:** [babych.github.io](https://babych.github.io/)

---

## 🚀 Flagship Deployments

| Project | Live Demo | Stack & Architecture | Highlights |
|---|---|---|---|
| **💡 СвітлоКарта України (SvitloMap)** | [svitlo.zeltanews.com](https://svitlo.zeltanews.com) / [Pages Mirror](https://svitlo-map.pages.dev) | Vanilla JS, HTML5 Canvas, Cloudflare Pages, SvitloBot API proxy | 60 FPS night-sky simulation of 25,897 settlements. Real-time 24h blackout schedules, 2,700+ SvitloBot IoT pingers cached at edge (`s-maxage=120`), dynamic zero-queue regional detection. |
| **🚗 Car Vibration & Pulse Analyzer** | [Launch App](https://car-vibration-analyzer.memory1024.workers.dev) | Cloudflare Worker, Pyodide (Wasm), PWA, Sensor APIs | Real-time spectral diagnosis (FFT, vehicle kinematics) and resting pulse seismocardiography via smartphone accelerometer. |
| **🎨 AuraStudio AI Creative Suite** | [Launch AuraStudio](https://aurastudio-ai.memory1024.workers.dev/) | Cloudflare Worker, Qwen 2.5 DiT, Telegram Bot API | Generative inpainting and styling suite with 100% facial identity anchoring, Telegram Stars checkout, and cloud inference. |
| **🐄 Dairy Farm Cloud Portal** | [Live Portal](https://dairy-farm-portal.pages.dev) | Cloudflare Pages, High-density Analytics | Herd telemetry, feed intake metrics, milk yield analytics, and interactive operations dashboard. |
| **⚡ IoT Grid & Telegram Widget** | [Dashboard](https://broadlink-telemetry-api.memory1024.workers.dev) / [Telegram Bot](https://t.me/svitlomonitor_fayna_bot?start=open) | Cloudflare Worker, D1 SQL, Telegram Mini App 10.4 | Lightweight (&lt;2 KB) in-chat power grid status matrix with sub-second reactive updates and WebCrypto authentication. |
| **☀️ Fayna SES Energy Portal** | [Launch Portal](https://fayna-ses-cq2.pages.dev) | Vue 3, TypeScript, Cloudflare Pages, PWA | Real-time solar PV generation, battery storage (BESS) state-of-charge, and 24h blackout resilience monitoring. |
| **🕹️ Interactive Playground** | [Open Playground](https://babych.github.io/playground/) | Pure HTML5 Canvas, Web Audio API, Vanilla JS | 1-shot procedural recreations: Super Mario Bros NES World 1-1, Atari Breakout 1976 Arcade with CRT shaders. |

---

## 🛠️ Core Technology Focus

- **Edge & Cloud Serverless:** Cloudflare Workers, Pages, D1 SQL, KV, Edge Caching, WebCrypto RFC 8030.
- **Client-Side DSP & Math:** HTML5 Canvas rendering at 60 FPS, Web Audio API procedural synthesis, Pyodide/WebAssembly FFT analysis.
- **Zero-Build & Ultra-Lean Architecture:** Production web apps built with vanilla JavaScript, modern Web Components, and minimal dependency footprint.
- **Autonomous Telemetry:** IoT pinger ingestion, real-time polling, and low-latency push notification architectures.

---

## 📂 Repository Structure

- `index.html` &mdash; Portfolio single-page layout (dark theme, responsive CSS grid, zero external framework dependencies).
- `playground/` &mdash; Interactive demos monorepo submodule/directory.

---

&copy; 2026 Dmytro Babych. Licensed under MIT.
