# ⚗️ ChemCheck — Chemical Compatibility Checker

A lightweight web app that instantly checks whether two chemicals are safe to mix or store together — built for students, lab assistants, and small labs who need a fast safety answer without digging through SDS sheets.

## 🚩 Problem

Chemical incompatibility accidents (toxic gas release, fire, explosion) are a recurring risk in school/college labs, industrial storage, and even households. Most people facing this risk — students, lab assistants, small facilities — don't have access to expensive enterprise chemical management software, and manually cross-referencing SDS documents is slow and error-prone under time pressure.

## 💡 Solution

Enter two chemicals → get an instant verdict:
- ✅ **Safe** — no known hazardous interaction
- ⚠️ **Caution** — handle carefully, explained why
- 🚫 **Dangerous** — do not mix, explained why

Each result includes a plain-language hazard explanation, GHS-style hazard tags, and storage guidance.

## ✨ Key Features

- Curated database of 25+ common lab chemicals and 19+ known dangerous pairs
- Rule-based fallback engine for oxidizer+flammable, acid+base, corrosive+corrosive patterns
- Zero friction: no login, no install, runs entirely in-browser
- Light/dark theme support, mobile responsive

## 🛠️ Tech Stack

HTML, CSS, vanilla JavaScript — single self-contained file, no dependencies.

## 🚀 Running Locally

Open `chem-compat.html` in any browser.

## 🔗 Live Demo

[Try it here](https://claude.ai/artifact/6Pqf5TUzZRy5LuSyore7Qz)

---
Built for **HackDevengers 2.0** 🏆