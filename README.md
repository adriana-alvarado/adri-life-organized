# Life Organized

A personal life tracker — goals, habits, and a life audit — all in one quiet, self-contained web page.

## How to use it

Just open `index.html` in any browser (double-click the file). There's nothing to install and no account to create. Everything you type saves automatically to that browser using `localStorage`.

## What's inside

- **Today** — a daily dashboard: a "🧭 pick up here" breadcrumb, your targets at a glance, today's goals and habits, a quick reflection space, and your current **level + XP bar**.
- **Goals** — separate lists for **daily**, **weekly**, **monthly**, and **quarterly** goals, pre-filled with your real plan (running, classes, robotics, CSWA), plus a quarter "theme." Check items off as you go; edit or add freely.
- **Targets** — your measurable goals with progress bars: longest run → 10k (with a 5k milestone), fastest mile → 8:00, body weight → 115 lbs, pull-ups → 1, Instagram → 700 followers, 2 new posts, 5 new friends. Set a **start** and update **now** as you progress; hit 100% for +120 XP.
- **Roadmaps** — every big goal broken into a checklist of **subgoals**, each with its own progress bar: Run a 10k, Sub-8 mile, Get a pull-up, Reach 115 lbs, Grow Instagram to 700, Build my social life, and the detailed Robotics + CSWA plan (with phases, a **"pick up here" breadcrumb**, and a definition of done). Add your own subgoals or whole new roadmaps anytime.
- **Habits** — a weekly habit grid. Add the habits you want to build, click a square per day, and watch your 🔥 streak grow. Navigate between weeks with the arrows.
- **Calories** — track what you eat and burn each day:
  - **Net calories** (eaten − burned) against a daily **budget**, with a progress bar that turns red if you go over, plus a separate **move goal** for calories burned.
  - **Two logs** — 🍓 *Eaten* and 🔥 *Burned* — where you add items with a name + kcal, or tap a **quick-add** chip (Banana, Greek yogurt, Run 30 min…) to log a typical food or workout in one click.
  - **Day navigation** with the arrows, so you can review or backfill past days.
  - **Meal reminders** — set the times you want a nudge to eat, flip reminders on, and the page pops a friendly "🍓 Time to eat!" toast (and a browser notification, if you allow them) at each time while the page is open.
  - A **glance card on Today** shows your net/budget and the next meal nudge, and taps through to the full tracker.

## 🍓 Calorie Cutie — the pop-out reminder app

Inside the `calories/` folder is a **separate, installable mini-app** built just for tracking calories and getting nudged to eat. It shares the exact same data as the Calories tab above (same browser, same device), so anything you log shows up in both.

**What makes it different from the tab:**
- **Install it like a real app.** Open `calories/` in Chrome or Edge and use the **⬇️ Install** button (or the install icon in the address bar). It gets its own dock/taskbar icon and opens in its own window — no browser tabs.
- **It pops out on its own.** At each meal time it plays a happy little **sound**, shows a system **notification** (even when you're in another app), flashes the taskbar title, and shows a big in-app banner with **“I'm eating”** and **“Snooze 10m”** buttons.
- **One-tap logging.** Quick-add chips for common foods and workouts, plus a custom add row.
- **Works offline** once installed.

> Heads-up: like any web app, reminders fire while the app is **open or minimized** (not when fully quit). Keep it running — and on Mac/Windows you can set it to launch at login so it's always there. Want reminders even when it's fully closed? That needs a native app; just ask and I'll build one.
- **Life Audit** — rate your satisfaction 1–10 across three areas:
  - Health & Fitness
  - Career & Finances
  - Personal Growth & Fun
  - Social & Community

  A **Wheel of Life** visualizes your balance at a glance, and a quarterly review box prompts you to pick what to invest in next. Tap **Save snapshot** to record the audit on a date so you can track it over time.
- **Progress** — your gamified dashboard:
  - **Level & XP** — earn XP for finishing goals (daily 15 · weekly 30 · monthly 50 · quarterly 100), checking off habits (10 each), and logging audits (40 each). Cross a threshold and a **level-up celebration** pops with confetti.
  - **Stats** — goals done, habit check-ins, best streak, active days, audits logged, total XP.
  - **Achievements** — milestone badges that unlock as you keep showing up.
  - **Audit trends** — a line chart of each area's satisfaction over every snapshot you've saved, so you can see what's improving and what's slipping.

## Your data

- **Saved locally** in your browser — private to you, never sent anywhere.
- **Export data** downloads a JSON backup. Keep it somewhere safe.
- **Import data** restores from a backup (useful when switching computers or browsers).
- **Reset all** wipes everything and starts fresh.

> Tip: because data lives in one browser, export a backup now and then — especially before clearing browser data.
