# 🌌 StudySphere 3D

<div align="center">

![StudySphere 3D Banner](https://raw.githubusercontent.com/sachin07-a/studysphere/main/public/favicon.svg)

### The Next-Generation 3D Academic Operating System & Student Productivity Suite
*Distraction-Free • Sensory Customization • Spaced Repetition • Offline-First Privacy*

[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-blue.svg?logo=typescript)](https://www.typescriptlang.org/)
[![React](https://img.shields.io/badge/React-19.x-61dafb.svg?logo=react)](https://react.dev/)
[![Vite](https://img.shields.io/badge/Vite-8.x-646CFF.svg?logo=vite)](https://vitejs.dev/)
[![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-3.x-38B2AC.svg?logo=tailwind-css)](https://tailwindcss.com/)
[![WebCrypto](https://img.shields.io/badge/Security-SHA--256_WebCrypto-emerald.svg)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Crypto_API)
[![License](https://img.shields.io/badge/License-MIT-purple.svg)](LICENSE)

[**Explore Live Repository**](https://github.com/sachin07-a/studysphere) • [**Report a Bug**](https://github.com/sachin07-a/studysphere/issues) • [**Request a Feature**](https://github.com/sachin07-a/studysphere/issues)

</div>

---

## 📖 Table of Contents
- [✨ Key Features](#-key-features)
- [🎨 Visual Theme & Color Studio](#-visual-theme--color-studio)
- [🧠 SuperMemo SM-2 Flashcards](#-supermemo-sm-2-flashcards)
- [📄 Split-Screen Local PDF Reader](#-split-screen-local-pdf-reader)
- [⏱️ Timestamp-Anchored Focus Engine](#️-timestamp-anchored-focus-engine)
- [📅 Calendar & Event Task Synchronization](#-calendar--event-task-synchronization)
- [📊 28-Day Habit Consistency Matrix](#-28-day-habit-consistency-matrix)
- [🎯 Exam Countdown & Syllabus Checklist](#-exam-countdown--syllabus-checklist)
- [📜 Automated Academic Report Card](#-automated-academic-report-card)
- [🔒 Security & Storage Architecture](#-security--storage-architecture)
- [🛠️ Tech Stack & Dependencies](#️-tech-stack--dependencies)
- [🚀 Quick Start & Installation](#-quick-start--installation)
- [📂 Project Directory Structure](#-project-directory-structure)
- [🛡️ Privacy Philosophy](#️-privacy-philosophy)

---

## ✨ Key Features

StudySphere 3D is designed to replace fragmented student tools (Notion, Anki, Forest, Spotify, and PDF readers) with a unified, high-performance academic workstation.

### 🌟 Core Highlights:
- **⏱️ Browser Tab Throttling-Immune Timer**: Precision timestamp tracking (`Date.now()`) with live browser tab title countdown and reload persistence.
- **🎨 Visual Theme & Color Studio**: 5 distinct UI surface physics (*Liquid-Glass UI, Glassmorphism, Minimalism, Skeuomorphism, Light Modern*) combined with 6 Radiant Color Palettes (30 possible visual pairings).
- **🧠 Active Recall & SM-2 Spaced Repetition**: 3D flip flashcards calculating mathematically optimal review intervals ($EF'$, $I(n)$).
- **📄 Native Split-Screen PDF Workstation**: Drag-and-drop local `.pdf` files with integrated Markdown note scratchpad, mini timer, and 1-click flashcard conversion.
- **📅 Interactive Calendar & Task Event Engine**: Schedule academic events that automatically convert to persistent tasks with streak and XP integration.
- **📊 28-Day GitHub-Style Habit Heatmap**: Activity matrix, 30-day habit success rate progress bars, and 14-day study vs. habit correlation area graphs.
- **🎯 Live Exam Countdown Ticker**: Days/hours/minutes ticker clock with color-coded urgency and syllabus unit checklist.
- **📜 Weekly Academic Report Card**: Formatted transcript modal with letter grade evaluation, printable stylesheet, and Markdown copy.
- **🎵 Lo-Fi Lounge & Procedural Web Audio**: Real-time synthesized binaural 40Hz focus waves, rain, cafe, and custom YouTube playlist streaming.
- **🔒 Multi-Account Isolated Database**: Salted SHA-256 WebCrypto password hashing, zero server dependencies, and 1-click JSON backup export/restore.

---

## 🎨 Visual Theme & Color Studio

StudySphere features an interactive theme engine that allows students to personalize both their **UI Surface Physics** and their **Vibrant Accent Palette**:

### 1. 🌌 The 5 UI Surface Styles:
1. 🔮 **Liquid-Glass UI**: Iridescent fluid reflections, specular highlights, and cosmic deep backdrops (`backdrop-blur-24px saturate(190%)`).
2. 🌌 **Glassmorphism**: Classic 3D cyberpunk frosted glass panels and glowing neon depth shadows.
3. ⚪ **Minimalism**: Zen Swiss matte monochrome, flat cards, crisp 1px zinc borders (`#27272a`), and zero distractions.
4. 🎛️ **Skeuomorphism**: Tactile 3D physical beveled hardware panels, embossed buttons, and mechanical dual drop-shadows.
5. ☀️ **Light Modern**: Clean daylight paper mode with crisp high-contrast readability.

### 2. 🌈 The 6 Radiant Color Palettes:
- 🌊 **Cyber Cyan**: Electric Blue & Ice Glow (`#06b6d4` & `#6366f1`)
- 🔮 **Cosmic Violet**: Radiant Magenta & Deep Nebula (`#d946ef` & `#8b5cf6`)
- 🍃 **Emerald Matrix**: Bioluminescent Neon Mint & Emerald (`#10b981` & `#06b6d4`)
- 🔥 **Solar Amber**: Warm Sunset & Solar Crimson (`#f59e0b` & `#f43f5e`)
- 🌸 **Sakura Rose**: Lofi Pastel & Neo Pink (`#f43f5e` & `#c084fc`)
- ⚡ **Electric Gold**: Cyber Honey & Radiant Orange (`#eab308` & `#ea580c`)

---

## 🧠 SuperMemo SM-2 Flashcards

StudySphere integrates the official **SuperMemo-2 (SM-2)** algorithm for active recall:
- **3D Card Flip**: Question on front, answer and explanation on back.
- **Confidence Ratings**:
  - `Again (1)`: Immediate reset ($I = 1\text{ day}$).
  - `Hard (2)`: Slight penalty ($I = 3\text{ days}$).
  - `Good (3)`: Standard expansion ($I = 6\text{ days}$).
  - `Easy (4)`: High ease multiplier ($I \ge 14\text{ days}$).
- **Formula**:
  $$EF' = EF + (0.1 - (5 - q) \times (0.08 + (5 - q) \times 0.02)) \quad (\text{bound } EF \ge 1.3)$$

---

## 📄 Split-Screen Local PDF Reader

- **Direct Local File Access**: Upload or drag-and-drop any `.pdf` lecture or research paper from your computer.
- **Zero Network Uploads**: Uses native browser `URL.createObjectURL(file)` to render securely offline inside an interactive viewer.
- **Split-Screen Productivity**:
  - Read lecture slides on the left.
  - Type markdown notes in the real-time scratchpad on the right.
  - Integrated mini Pomodoro focus timer.
  - **1-Click Flashcard Creator**: Instantly bridge notes into an active recall flashcard deck.

---

## ⏱️ Timestamp-Anchored Focus Engine

- **Tab Throttling Immunity**: Anchored to real-world clock timestamps (`Date.now()`). When switching tabs or minimizing the browser, zero seconds are lost.
- **Instant Tab Reconciliation**: Listens to `visibilitychange` and `focus` events to reconcile time the moment you return.
- **Reload & Refresh Persistence**: If you hit `F5` or refresh the browser mid-session, the timer resumes counting from the exact remaining second.
- **Live Tab Title Display**: Displays real-time countdown on your browser tab (`⏳ (24:45) StudySphere Focus`).

---

## 📅 Calendar & Event Task Synchronization

- **Event Scheduling**: Double-click any day cell or click **"+ Schedule Event"** to plan upcoming exams, deadlines, or presentations.
- **Automatic Task Conversion**: Scheduled events are stored in user data as actionable `Tasks` with linked subjects and priority levels.
- **Direct Check-Off**: Mark tasks and events completed right from the Calendar timeline, triggering **Celebration Confetti 🎉**, **XP gains**, and **Daily Streak** increments.

---

## 📊 28-Day Habit Consistency Matrix

- **GitHub-Style Heatmap Grid**: 4-week activity matrix with dynamic glowing color intensity:
  - ⬛ Dark: 0% completed
  - 🟩 Emerald: 30% - 70% completed
  - 🟢 Vibrant Green: 75% - 99% completed
  - 🌟 **Glowing Cyan & Gold**: **100% Perfect Day!**
- **30-Day Adherence Bars**: Visual success rate percentages and unbroken streak badges for every individual habit.
- **14-Day Correlation Graph**: Area chart overlaying completed daily habits against logged study hours.

---

## 🎯 Exam Countdown & Syllabus Checklist

- **Live Countdown Ticker Clock**: Real-time Days : Hours : Minutes : Seconds ticker.
- **Urgency Indicators**: Color-coded badges (`High Urgency < 7d`, `Medium < 30d`, `Target Scheduled`).
- **Syllabus Mastery Checklist**: Break down course units into checkable sub-topics with live mastery percentage progress bars.

---

## 📜 Automated Academic Report Card

- Formatted official academic transcript generator summarizing weekly performance.
- Evaluates **Total Study Hours**, **Habit Adherence Rate**, **Task Completion**, and computes an **Overall Academic Letter Grade (A+, A, B, etc.)**.
- Features 1-click **Print / Save as PDF** stylesheet and **Copy Markdown Summary**.

---

## 🔒 Security & Storage Architecture

1. **Client-Side Isolated Storage**:
   - Offline-first document database managed by `src/lib/storage.ts` in browser `localStorage`.
   - Complete data isolation per user account profile (`UserAccount`).
2. **WebCrypto SHA-256 Passwords**:
   - Passwords are salted with `_studysphere_salt_2026` and cryptographically hashed via `crypto.subtle.digest('SHA-256')`. Plaintext passwords are never stored.
3. **1-Click Data Portability**:
   - Export full JSON database backups from **Settings ➔ Export Backup** and restore them on any computer or browser.
4. **Cloud Database Ready (Optional)**:
   - Configured in `src/lib/supabase.ts` for optional PostgreSQL cloud synchronization via environment variables (`VITE_SUPABASE_URL` and `VITE_SUPABASE_ANON_KEY`).

---

## 🛠️ Tech Stack & Dependencies

| Layer | Technology |
| :--- | :--- |
| **Language** | TypeScript (v5.x) + ECMAScript Modern |
| **Frontend Framework** | React 19 (Function Components, Hooks, Context API) |
| **Build Tool & Bundler** | Vite 8.x (Rolldown engine with chunk splitting) |
| **Styling & Design** | Tailwind CSS 3.x + Glassmorphism & Custom CSS Variables |
| **Charts & Telemetry** | Recharts (Responsive Area, Bar, Pie & Line charts) |
| **Icons** | Lucide React (High-performance SVG icons) |
| **Micro-Interactions** | Canvas-Confetti (Level-ups & streak rewards) |
| **Audio Synthesis** | Web Audio API (`AudioContext`, `BiquadFilter`, `OscillatorNode`) |
| **Security** | WebCrypto API (`SHA-256` hashing & salting) |
| **Cloud Connector (Optional)** | `@supabase/supabase-js` |

---

## 🚀 Quick Start & Installation

### 1. Clone the Repository
```bash
git clone https://github.com/sachin07-a/studysphere.git
cd studysphere
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Start Development Server
```bash
npm run dev
```
Open your browser and navigate to `http://localhost:5173`.

### 4. Build for Production
```bash
npm run build
```

---

## 📂 Project Directory Structure

```text
studysphere/
├── public/                     # Static assets & icons
├── src/
│   ├── components/
│   │   ├── 3d/                 # Interactive HTML5 Canvas 3D particle systems
│   │   ├── achievements/       # Tiered achievement unlock tree & XP badges
│   │   ├── analytics/          # 28-day heatmap, adherence bars & study trends
│   │   ├── auth/               # Glassmorphic Login / Signup / Guest demo switcher
│   │   ├── calendar/           # Month grid, event scheduler & task converter
│   │   ├── dashboard/          # Central HUD, 3D productivity orb, daily actions
│   │   ├── exams/              # Countdown ticker clocks & syllabus checklists
│   │   ├── flashcards/         # 3D Flip cards & SuperMemo SM-2 spaced repetition
│   │   ├── goals/              # Milestones & study hour targets
│   │   ├── habits/             # Daily habit tracker & multi-activity streak engine
│   │   ├── layout/             # Header, Sidebar, MobileNav, ThemeSelectorModal
│   │   ├── music/              # Floating player dock & YouTube Lo-Fi lounge
│   │   ├── notes/              # Markdown notes repository with tagging & pinboard
│   │   ├── onboarding/         # First-time scholar setup wizard
│   │   ├── pdf/                # Local PDF drag-and-drop workstation & scratchpad
│   │   ├── reports/            # Printable weekly academic report card modal
│   │   ├── settings/           # Profile editor, theme studio & JSON backup export
│   │   ├── subjects/           # Subject catalog & study hour allocations
│   │   ├── tasks/              # High/Medium/Low priority task matrix
│   │   └── timer/              # Timestamp-anchored focus timer & Zen chamber
│   ├── context/
│   │   ├── AuthContext.tsx     # WebCrypto auth state & XP level progression
│   │   ├── StudyContext.tsx    # Central study state, persistent timers & streak sync
│   │   └── ThemeContext.tsx    # 5 Surface themes & 6 Accent Color palettes
│   ├── lib/
│   │   ├── audio.ts            # Procedural Web Audio sound generator
│   │   ├── mockData.ts         # Initial demo starter data
│   │   ├── productivity.ts     # Multi-activity streak algorithm & scoring
│   │   ├── spacedRepetition.ts # SuperMemo SM-2 mathematical calculation engine
│   │   ├── storage.ts          # LocalStorage document repository & account isolation
│   │   └── supabase.ts         # Optional PostgreSQL cloud connector
│   ├── styles/
│   │   └── globals.css         # Theme CSS variables, glowing shadows & animations
│   ├── types/
│   │   ├── index.ts            # Core TypeScript data interfaces
│   │   └── music.ts            # YouTube station & track definitions
│   ├── App.tsx                 # View router & layout shell
│   └── main.tsx                # React application entry point
├── package.json
├── tailwind.config.js
├── tsconfig.json
└── vite.config.ts
```

---

## 🛡️ Privacy Philosophy

- **Zero Surveillance**: StudySphere does not send your study habits, notes, or uploaded PDFs to third-party tracking servers.
- **Local Sovereignty**: All your academic data lives on your device and can be backed up as an open JSON file whenever you wish.

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

<div align="center">

Crafted with 🌌 for students and scholars worldwide.

**[⭐ Star this repository on GitHub](https://github.com/sachin07-a/studysphere)**

</div>
