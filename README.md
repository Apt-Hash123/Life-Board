# Life Board

A bright, simple tracker for daily tasks, flexible habits, long-term goals, lists, notes and wins.
Designed and built by Shelly Khanuja.

It installs on a phone like an app, works offline, and keeps all data on the device (browser local storage). Nothing is sent to a server.

Highlights: smart quick add ("Laundry every sun #errands !"), swipe to complete or delete, a morning check-in for unfinished tasks, a swipeable habit check-in deck, habit and goal streaks with linked goals, a year heatmap and performance charts, inline notes with checkboxes, resizable boards, and a Ctrl/Cmd+K command bar on desktop.

## What's in this folder

| File | What it does |
|---|---|
| `index.html` | The whole app |
| `manifest.webmanifest` | Lets phones install it with its own icon and name |
| `sw.js` | Lets the app open without internet |
| `icons/` | App icons |
| `og.png` | Preview image for LinkedIn and other link previews |
| `vercel.json` | Small hosting settings for Vercel |

## Put it online with Vercel (no coding)

1. Unzip this folder.
2. On github.com, create a free account if needed, then **New repository** → name it `life-board` → Public → **Create repository**.
3. On the new repo page click **uploading an existing file**, drag in everything from the unzipped folder (including the `icons` folder), then **Commit changes**.
4. On vercel.com, **Sign up with GitHub** → **Add New… → Project** → **Import** `life-board` → Framework preset **Other** → **Deploy**.
5. You get an address like `life-board-abc.vercel.app`. You can change it under **Project → Settings → Domains**.
6. For the LinkedIn preview image: in GitHub open `index.html`, click the pencil, find `__SITE_URL__` (2 places), replace it with your address (for example `https://life-board-abc.vercel.app`), and commit. Vercel updates the site by itself in about a minute.

## Install it on your phone

- **iPhone:** open your Vercel address in **Safari** → Share button → **Add to Home Screen**.
- **Android:** open it in **Chrome** → menu → **Install app**.

Always open it from the home-screen icon. On iPhone the installed app keeps its own storage, separate from Safari.

## Move your board in from the Claude version

1. In the Claude version: profile (top right) → **Categories & backup** → **Copy backup**.
2. In the installed app: choose **Start my own board** → profile → **Categories & backup** → **Paste a backup** → paste → **Replace my board with this backup**.

## Keep your data safe

Your data lives only on that device. About once a month: profile → **Categories & backup** → **Download backup file**, and keep it somewhere safe (iCloud Drive, Google Drive, email to yourself). To restore, use **Restore from file**.

## For people who visit from LinkedIn

Visitors see a welcome screen with **Explore with example data**, so they can try every feature without signing up. Their data stays in their own browser and never mixes with yours.
