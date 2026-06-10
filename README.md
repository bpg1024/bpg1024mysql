# PnL Calendar

A simple, self-contained trading P&L calendar. Track your daily trades on a monthly calendar with color-coded profit/loss days and monthly stats.

## Usage

Open `index.html` in any browser — no install, no server, no dependencies.

## Install on iPhone (PWA)

The app is a Progressive Web App — it can be installed on your iPhone home screen and works offline.

1. **Host it**: merge this branch to `main` and enable GitHub Pages for the repo
   (Settings → Pages → Source: **GitHub Actions**). The included workflow deploys
   automatically and gives you a URL like `https://<user>.github.io/<repo>/`.
2. **Open that URL in Safari** on your iPhone.
3. Tap the **Share** button → **Add to Home Screen** → **Add**.

It now launches full-screen from its own icon like a native app, and keeps working
without an internet connection. Trade data is stored on the device.

- **Click a day** to log trades (symbol, P&L, optional notes) or delete existing ones.
- Days are shaded **green** (net profit) or **red** (net loss) with the daily total shown.
- Monthly stats up top: total P&L, day win rate, green/red day count, best/worst day, and trade count.
- Navigate months with the arrows or jump back with **Today**.
- **Export / Import** your data as JSON for backup or moving between devices.

Data is stored in your browser's `localStorage`, so it persists between visits on the same browser.
