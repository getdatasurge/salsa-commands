# Salsa: Saucy Command Trainer

A Taco Bell-themed flashcard app for training Salsa the Aussie Shepherd with 100 saucy dog commands across 6 sauce-packet categories, with audio pronunciation, search, and keyboard shortcuts.

**[Live Demo](https://getdatasurge.github.io/salsa-commands/)**

## Features

- **100 Saucy Commands** across 6 categories: Obedience (Mild), Tactical (Diablo), Movement (Verde), Search (Hot), Utility (Fire), Environmental (Breakfast)
- **Audio Pronunciation** via Web Speech API with adjustable speed (slow/normal/fast)
- **3D Flashcard Flip** with bounce animation
- **Progress Tracking** — seen cards, mastered cards, and streak counter persisted in localStorage
- **Mobile Responsive** — slide-over drawer navigation, touch swipe for card navigation, scrollable filter chips
- **Category Filtering** — quick filter chips and sidebar accordion
- **Keyboard Shortcuts** — Space (flip), Arrow keys (navigate), S (speak), M (mark mastered)
- **Onboarding** — first-visit welcome overlay with shortcut hints
- **Accessible** — ARIA labels, live regions, skip-to-content link, focus management

## Usage

Open `index.html` in any modern browser. No build step or server required.

### Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Space` | Flip card |
| `→` | Next card |
| `←` | Previous card |
| `S` / `A` | Speak word |
| `M` | Toggle mastered |

## Tech Stack

- HTML / CSS / JavaScript (single file, no build tools)
- [Tailwind CSS](https://tailwindcss.com/) via CDN
- [Web Speech API](https://developer.mozilla.org/en-US/docs/Web/API/SpeechSynthesis) for audio
- GitHub Pages for hosting
