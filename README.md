# WordMaster Academy

A mobile-friendly English vocabulary learning website built with HTML, CSS, and vanilla JavaScript. It does not require Base44, Replit, a build step, or external JavaScript libraries.

## Run locally

Open `index.html` in a modern browser. For best compatibility, serve the folder with a simple static web server. Speech synthesis voices and local storage behavior depend on the browser and device.

## Features

- Reference-inspired purple-framed classroom with an included vector classroom illustration.
- Responsive mobile interface with animated vocabulary stickers.
- 200+ vocabulary records across 12 categories, with Indonesian meanings and example sentences.
- **English Audio → English Answers** listening mode. The prompt speaks an English word and all answer choices are English words.
- **Indonesian Audio → English Answers** listening mode. The prompt speaks the Indonesian meaning and all answer choices remain English words.
- Word Flashcards, Word Scramble, and Picture Match games.
- XP, coins, daily quests, badges, category progress, and a vocabulary review list.
- A dedicated Streak menu with an evolving flame companion: yellow at 0–24 days, red at 25–49, purple at 50–99, and light blue at 100+ days.
- A streak is counted once per calendar day when the website is opened. Reopening or refreshing the site on the same day does not add another day; missing a calendar day resets the next streak to day 1.
- Progress is stored in localStorage on the current browser/device.
- Sound toggle, reduced-motion support, editable profile nickname, and reset-demo-progress button.

## Important notes

- The streak is a local daily-visit streak, not an account-based login system. There is no server, account authentication, or cross-device synchronization in this standalone version. Clearing browser data can reset saved progress.
- Pronunciation uses the browser Speech Synthesis API. English and Indonesian voices available on the device may differ.
- The classroom illustration is an included SVG asset at `assets/classroom.svg`. The classroom scene is vector artwork rather than a live 3D GLB model.
