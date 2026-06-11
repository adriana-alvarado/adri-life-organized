# 🍓 Calorie Cutie

A small, **standalone** calorie tracker that estimates what you burn automatically and reminds you to eat. It runs entirely in your browser, saves only on your device, and is **completely independent** — it does not share data with anything else.

## Install it as an app

1. Open this `calories/` folder's `index.html` in **Chrome or Edge** (over a real address — e.g. your GitHub Pages URL `…/adri-life-organized/calories/`).
2. Click the **install icon** in the address bar, or open ⚙️ Settings → **⬇️ Install as an app**.
3. It gets its own dock/taskbar icon and opens in its own window. It works offline after that.
4. On Mac/Windows you can set it to **launch at login** so it's always running in the background.

## What it tracks

**🔥 Calories burned — calculated automatically**
- **Resting burn** ticks up live through the day from your body stats (the Mifflin–St Jeor BMR formula, prorated by time of day). A finished past day counts the full day.
- **Runs** are estimated from your weight + distance. Add the minutes too and it uses the ACSM running formula for a pace-aware estimate (and shows your min/mile or min/km).
- **Steps** convert to calories scaled by your weight — type a total or tap +500 / +1k.
- **Workouts** — tap a preset (pilates, strength, cycling…) or add your own with a calorie amount.

**🍓 Calories eaten** — quick-add chips for common foods, or type your own.

Your **net** (eaten − burned) is shown big against your daily **budget**, with a live breakdown of every burn source.

## Reminders to eat

Set the times you want a nudge in ⚙️ Settings and turn reminders on. At each time the app plays a sound, shows a system notification, flashes the taskbar, and pops an in-app banner with **“I'm eating”** and **“Snooze 10m”**.

> Reminders fire while the app is **open or minimized** (not when fully quit), since it's a web app. Keep it running — launching it at login is the easy fix.

## Your stats power everything

The very first time you open the app, a **“Let's set up your numbers”** card asks for your **sex, age, height, and weight** (toggle imperial/metric) and your daily budget. The moment you enter them, every burn estimate becomes yours — your BMR is shown right there as you type.

After that, the summary always shows a **“📐 from your stats: ♀ · 25y · 5'5" · 120 lb · BMR 1289 — tap to edit”** line, so it's clear the numbers come from your data. Tap it (or the ⚙️ gear) anytime to update your weight, etc., and all the calculations refresh instantly. Everything is saved locally on this device only.

## Note

All burn figures are **estimates** based on population formulas, not exact measurements. Great for tracking trends day to day; not a medical instrument.
