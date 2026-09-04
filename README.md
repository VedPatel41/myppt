# VAC-II Presentation — Computing & AI in Agriculture

> An interactive, modern HTML5 web presentation built with **Reveal.js** and **Tailwind CSS** featuring glassmorphic UI design, examining computer fundamentals, IoT, and AI applications in modern agriculture.

[![Presentation Engine](https://img.shields.io/badge/Reveal.js-4.x-red.svg)](https://revealjs.com/)
[![Styling](https://img.shields.io/badge/Tailwind_CSS-CDN-38B2AC.svg)](https://tailwindcss.com/)
[![Course](https://img.shields.io/badge/Course-VAC--II-green.svg)](#)
[![Institution](https://img.shields.io/badge/College-CP_College_of_Agriculture_SDAU-blue.svg)](#)

---

## 📋 Overview

This repository hosts a web-based presentation developed for the **VAC-II (Value Added Course)** assignment on the topic: **"Comparative Study of Computing & AI in Agriculture"**. 

Built using the **Reveal.js** HTML presentation framework combined with **Tailwind CSS**, it features a dark glassmorphic design theme with convex slide transitions, responsive tables, grid comparisons, and keyboard navigation.

---

## 🎯 Key Topics Covered

The presentation spans 12 structured slides organized into progressive conceptual modules:

| Slide # | Topic | Key Focus Areas |
|:-------:|:------|:----------------|
| **01** | Title & Introduction | Presentation credentials, course information |
| **02** | Agriculture Informatics & AI | Defining IT data techniques & AI automation in farming |
| **03** | Primary vs. Secondary Memory | Volatility, access speed, and CPU bus architecture |
| **04** | SRAM vs. DRAM | Speed, cost trade-offs, and cache vs. main memory roles |
| **05** | RAM vs. ROM | Temporary working memory vs. non-volatile BIOS firmware |
| **06** | GUI vs. CLI | Graphical mouse/window interfaces vs. command-line efficiency |
| **07** | Compiler vs. Interpreter | Whole-code compilation vs. line-by-line runtime execution |
| **08** | IoT vs. Big Data in Agriculture | Real-time sensor collection vs. predictive analytics |
| **09** | Computing Fundamentals vs. AI | Fixed-instruction logic vs. intelligent adaptive learning |
| **10** | AI vs. Robotics in Agriculture | Crop health/weed analysis vs. autonomous tractors and drones |
| **11** | Conclusion | Synthesis on productivity, precision farming, and sustainability |
| **12** | Submission & Acknowledgments | Department of Statistics, CP College of Agriculture, SDAU |

---

## 💻 Tech Stack & Features

- **Framework**: [Reveal.js](https://revealjs.com/) (CDN-based)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) (CDN) with custom Glassmorphic styling (`backdrop-filter: blur(10px)`)
- **Presentation Controls**:
  - `hash: true` — URL updates per slide for direct linking / bookmarking
  - `slideNumber: true` — Real-time slide counter
  - `transition: "convex"` — Smooth 3D convex slide transitions
  - `backgroundTransition: "fade"` — Clean visual fades between themes
- **Responsive Design**: Adapts seamlessly to projection displays, laptops, tablets, and mobile browsers.

---

## 🚀 How to Run Locally

Since this is a client-side HTML5 presentation with CDN-hosted dependencies, running it is instantaneous:

### Option 1: Direct Browser Launch
Simply double-click or open `index.html` in any modern web browser (Chrome, Edge, Firefox, Safari).

### Option 2: Local HTTP Server (Recommended)
Using Python:
```bash
python -m http.server 8000
```
Then navigate to `http://localhost:8000` in your browser.

Using Node.js / `npx`:
```bash
npx serve .
```

---

## ⌨️ Presentation Navigation Controls

- **Next Slide**: `Space`, `Right Arrow`, or `Down Arrow`
- **Previous Slide**: `Left Arrow` or `Up Arrow`
- **Overview Mode**: Press `O` or `Esc` to zoom out into slide grid view
- **Full Screen**: Press `F` to toggle full-screen presentation mode
- **Speaker Notes**: Press `S` to open the presenter view window

---

## 👤 Author & Academic Details

- **Presented by**: Henil Patel (Roll No. 80 | Batch-II | Class-A)
- **Department**: Department of Statistics
- **Institution**: C.P. College of Agriculture, S.D. Agricultural University (SDAU)
- **Course**: VAC-II (Value Added Course)
