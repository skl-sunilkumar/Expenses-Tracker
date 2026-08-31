# 💰 Daily Expense Tracker

A lightweight, installable web app to track daily transport and other expenses
against your monthly pocket money — runs entirely in your browser, works fully
offline, and needs no backend or database server.

**Live app:** https://skl-sunilkumar.github.io/Expenses-Tracker/index.html

## Features

- **Transport expenses** — log auto, bike, or mofussil bus rides
  - Bus rides capture AC / Deluxe / Normal category and bus number
  - Route picker with common routes pre-loaded, or type a custom From → To
  - Payment method tracking: Cash, G-Pay, WhatsApp Pay, or Other
- **Other expenses** — food, clothes, stationary, or your own custom category
- **Dashboard** — automatic monthly math:
  - Total spent, remaining balance
  - Daily average spend
  - Projected month-end total based on your current spending pace
  - Category and transport-type breakdowns
- **History** — view and delete any entry for the month
- **Pocket Money** — set your budget per month

## Install it as an app (Android)

1. Open the live link above in Chrome on your phone.
2. Tap **Install app** when prompted (or ⋮ menu → **Install app**).
3. It's now in your app drawer like any other app — and works fully offline
   after the first load.

(On iPhone: Safari → Share icon → **Add to Home Screen**.)

## Tech

Plain HTML, CSS, and JavaScript — no frameworks, no build step. Data is stored
locally in your browser (`localStorage`), so nothing you enter ever leaves your
device. A service worker caches the app for offline use once installed.

## Privacy

All expense data stays on your device. This app makes no network requests and
has no backend — the only thing hosted on GitHub Pages is the app's code itself.
