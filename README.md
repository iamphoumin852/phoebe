# Phoebe

A minimal, mobile-friendly tracker for dietary tiers — Meat, Fish, Vegetarian, Vegan.

Log each meal of your day with one tap and see your flesh-free index: the percentage of all logged meals that were vegetarian or vegan (fish optional).

## Features

- One-tap meal logging across 4 dietary tiers
- All-time flesh-free index as the headline number
- Timezone-aware daily reset and meal slot times
- Catch-up prompts for meals you forgot to log yesterday
- 7-day "bead string" visual showing recent history at a glance
- Configurable meals per day, slot times, default tier, and index definition
- All data stored locally on your device (localStorage) — no account, no server

## Usage

Open `index.html` in a mobile browser. For an app-like experience, add it to your home screen (Safari: Share → Add to Home Screen; Chrome: Menu → Add to Home Screen).

## Settings

Tap the timezone label or the settings icon to configure:

- **Default tier** — fallback tier preference
- **Timezone** — drives the daily reset and meal slot timing
- **Meals per day** — 1–6, default 3
- **Meal slot times** — when each meal "activates" for logging
- **Flesh-free index** — whether fish counts toward the index
- **Reset all data** — clears all logged history

## Privacy

No data leaves your device. Everything is stored in browser localStorage.

## Hosting

This is a static single-file app — deploy via GitHub Pages, Netlify, or any static host. No build step required.
