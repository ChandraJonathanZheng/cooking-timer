# 🍳 Cooking Timer

A fast, mobile-friendly cooking timer web app — works great inside the **LINE in-app browser**.

**Live demo:** `https://chandrajonathanzheng.github.io/cooking-timer/`

## Features

- 36 food presets across 7 categories (Eggs, Meat, Seafood, Pasta, Vegetables, Baked, Drinks)
- Multiple timers running at the same time
- Custom timer (hours / minutes / seconds)
- Sound alert + phone vibration when done
- Snooze 1 minute if you're not ready
- Share link directly to LINE chat
- Works offline — no login, no server needed
- Optimized for mobile (iOS & Android)

## How to deploy on GitHub Pages (free hosting)

1. **Create a new GitHub repository** at https://github.com/new
   - Name it anything you like (e.g. `cooking-timer`)
   - Set it to **Public**
   - Do NOT add a README (you already have one)

2. **Upload the files** — drag `index.html` and `README.md` into the repo via the GitHub web UI, or use git:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin https://github.com/<your-username>/<your-repo>.git
   git push -u origin mainh
   ```

3. **Enable GitHub Pages:**
   - Go to your repo → **Settings** → **Pages**
   - Under "Source", select **Deploy from a branch**
   - Branch: `main` / folder: `/ (root)` → **Save**

4. **Your app is live in ~1 minute** at:
   ```
   https://chandrajonathanzheng.github.io/cooking-timer/
   ```

5. **Share in LINE** — open the link inside LINE browser, tap the green LINE button at the bottom-right to share with friends!

## Files

| File | Description |
|------|-------------|
| `index.html` | The entire app — HTML, CSS, and JS in one file |
| `README.md` | This file |

## Tech stack

- Vanilla HTML / CSS / JavaScript — no frameworks, no build step
- Web Audio API — timer done sound (no external audio files)
- Vibration API — phone vibration on completion
- Page Visibility API — keeps timers accurate when you switch tabs

## License

MIT — free to use, modify, and share.
