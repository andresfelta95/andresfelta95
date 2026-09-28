<h1 align="center">Hi, I'm Andres Tangarife 👋</h1>
<h3 align="center">Electronics Technologist · Embedded &amp; PCB · Full-Stack Web</h3>
<p align="center"><em>Building from silicon to cloud: boards, firmware, and the apps and servers that talk to them.</em></p>

<p align="center">
  <a href="https://paisbru.com"><img src="https://img.shields.io/badge/Portfolio-paisbru.com-0E7490?style=for-the-badge&labelColor=05060D" alt="Portfolio: paisbru.com" /></a>
  <a href="https://www.linkedin.com/in/andres-tangarife-267737126/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge" alt="LinkedIn" /></a>
  <a href="mailto:andresfelta95@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

## About me

I work where hardware meets software.

**By day** I'm an Electronics Technologist working on oilfield and downhole electronics: PCB inspection and quality control, firmware integration, and instrumentation (HART devices, 4–20 mA loops, Modbus RTU). Before that I did field applications and QC for industrial combustion controllers, including test-fixture development.

**After hours** I design boards, write bare-metal firmware, and build full-stack apps that run on my own home server at **[paisbru.com](https://paisbru.com)**.

- 🎓 Computer Engineering Technology diploma (NAIT), with a background in Petroleum Engineering
- 🧪 Test and inspection automation, e.g. a camera + QR-code PCB inspection station tied into LabVIEW with Python
- 🌎 Bilingual: English / Español
- 📍 Edmonton, Alberta, Canada

---

## Featured projects

### 🔌 Hardware & embedded

- **[🎯 Interactive Dartboard](https://github.com/andresfelta95/Point-Detector)** — ESP32 firmware in MicroPython reads ultrasonic sensors through a multiplexer to find where each dart lands and pushes the score over Wi-Fi in real time; a React Native app shows the live game.<br>`ESP32` `MicroPython` `React Native` `Expo` · [firmware](https://github.com/andresfelta95/Point-Detector) · [mobile app](https://github.com/andresfelta95/InteractiveDartBoard_MobileApp)
- **[⏱️ ComputerUseNanny](https://github.com/andresfelta95/ComputerUseNanny)** — a custom ATmega328P PCB: a VL53L1X time-of-flight sensor notices when you're at the desk, and an LED strip plus a 128×32 OLED give feedback on screen time. Bare-metal C with register-level I²C, UART, ADC and timer drivers.<br>`C` `AVR` `I²C` `PCB design`
- **[🧰 ATmega328P drivers & demos](https://github.com/andresfelta95/ATmega328pDemos)** — the AVR driver set behind it (I²C/TWI, UART, ADC, timers, SSD1306 OLED, WS2812 LEDs, LM75A, VL53L1X), plus [ESP32 / ESP8266 MicroPython experiments](https://github.com/andresfelta95/ESP32_MicroPython_Demos) with sensors, NeoPixels, OLEDs and multiplexers.

### 🌐 Web apps, live on my home server

- **[⚡ Workbench / Banco de Trabajo](https://electronics.paisbru.com)** — a free, bilingual (EN/ES) interactive electronics course. Every concept ships with an instrument you operate; circuits are live SVG components, so values update as you turn a knob. A 12-module path from Ohm's law to PCB design, with the first lessons live.<br>`Angular` `TypeScript` `Signals` `Static prerender` · [live](https://electronics.paisbru.com) · [code](https://github.com/andresfelta95/workbench-electronics)
- **[🎸 MakeTabs](https://tabs.paisbru.com)** — turns any Spotify track into guitar tabs or a 16-bit chiptune. Songsterr first, with an ML fallback (Demucs source separation → basic-pitch transcription) on a GPU; playback runs on a Web Audio synth.<br>`React` `TypeScript` `FastAPI` `Demucs` `PostgreSQL` · [live](https://tabs.paisbru.com) · [code](https://github.com/andresfelta95/MakeTabs)
- **[📈 AMD Price Tracker CA](https://amd.paisbru.com)** — tracks Ryzen and Radeon prices across Canadian retailers. Scheduled scrapers (Cheerio + a Playwright service) snapshot prices twice a day into PostgreSQL, with history charts and per-brand GPU variants.<br>`Next.js` `TypeScript` `PostgreSQL` `Playwright` · [live](https://amd.paisbru.com) · [code](https://github.com/andresfelta95/amd-price-tracker)
- **[⚽ FIFA Tracker](https://fifa.paisbru.com)** — World Cup 2026 sticker-album tracker with live scores: owned / missing / duplicates, QR swap codes, a community leaderboard with swap matching, email / Google / Microsoft sign-in with 2FA, live standings and a knockout bracket.<br>`React` `Vite` `Express` `PostgreSQL` · [live](https://fifa.paisbru.com)
- **[🕹️ paisbru.com](https://paisbru.com)** — my portfolio. Next.js 14 with a pixel-art, cyberpunk circuit-board look: every sprite and copper trace is generated SVG, not image files.<br>`Next.js` `TypeScript` `Tailwind CSS` · [live](https://paisbru.com) · [code](https://github.com/andresfelta95/portfolio)

### 🖥️ Infrastructure

- **Home server** — a WSL2 + Docker Compose stack running 24/7 behind a Cloudflare Tunnel with no open ports: Cloudflare Access in front of private apps, nginx, PostgreSQL / MySQL / MongoDB / Redis, Uptime Kuma monitoring and nightly database backups. It serves everything above.

### 🚧 On the bench

- **🎮 T113-S3 handheld console** — a 4-layer KiCad 9 board around the Allwinner T113-S3: 720p HDMI through an LT8618SX bridge, 240p composite for CRTs, Bluetooth controllers, an RP2040 for panel firmware, and Linux + RetroArch.
- **👊 Boulevard of the Broken Pixels** — an original 16-bit pixel-art beat-'em-up with a punk-rock cast, built in Godot 4.
- **🎨 Retro Creator** — an Electron desktop app with Claude-powered pixel-art tools (palette generation, sprite critique with vision, tileset planning) and a local ComfyUI + SDXL Turbo pipeline on the GPU.
- **🌲 Grove Guide** — an API-first guide to local businesses in Spruce Grove, AB: Next.js 15 and PostgreSQL full-text search with typo tolerance.

---

## Stack

| Layer | Tools |
| :-- | :-- |
| **Embedded & hardware** | ![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black) ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![MicroPython](https://img.shields.io/badge/MicroPython-2B2728?style=flat-square&logo=micropython&logoColor=white) ![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white) ![ATmega328P](https://img.shields.io/badge/ATmega328P-4B5563?style=flat-square) ![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=flat-square&logo=kicad&logoColor=white) ![Altium Designer](https://img.shields.io/badge/Altium_Designer-A5915F?style=flat-square) ![LabVIEW](https://img.shields.io/badge/LabVIEW-FFDB00?style=flat-square&logo=labview&logoColor=black) |
| **Protocols & instrumentation** | HART · 4–20 mA loops · Modbus RTU · I²C · SPI · UART |
| **Web & mobile** | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Expo](https://img.shields.io/badge/Expo-1C2024?style=flat-square&logo=expo&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) |
| **Backend & data** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) |
| **Infrastructure** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![nginx](https://img.shields.io/badge/nginx-009639?style=flat-square&logo=nginx&logoColor=white) ![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Uptime Kuma](https://img.shields.io/badge/Uptime_Kuma-15803D?style=flat-square&logo=uptimekuma&logoColor=white) |
| **AI & tooling** | ![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=claudecode&logoColor=white) ![Anthropic API](https://img.shields.io/badge/Anthropic_API-191919?style=flat-square&logo=anthropic&logoColor=white) ![GitHub Copilot](https://img.shields.io/badge/GitHub_Copilot-000000?style=flat-square&logo=githubcopilot&logoColor=white) ![Cursor](https://img.shields.io/badge/Cursor-000000?style=flat-square&logo=cursor&logoColor=white) ![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white) ![Godot](https://img.shields.io/badge/Godot-478CBF?style=flat-square&logo=godotengine&logoColor=white) |

---

<p align="center"><em>Open to opportunities and collaborations, especially anything that needs someone as comfortable with a soldering iron as with a Dockerfile.</em></p>
