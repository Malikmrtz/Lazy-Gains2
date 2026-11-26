# Lazy Gains

A phone-friendly meal plan, shopping list, snack guide and weight tracker. No build step. It installs like an app and works offline after the first visit.

## Files

`index.html` (the app), `logo.svg` (logo and app icon), `manifest.webmanifest` and `sw.js` (install and offline support).

## Put it on GitHub Pages (free)

1. Create a new **public** repository called `lazy-gains`.
2. **Add file > Upload files**, drop in all five files from this folder, then **Commit changes**.
3. **Settings > Pages**: Source **Deploy from a branch**, branch `main`, folder `/ (root)`, then **Save**.
4. After a minute the app is live at `https://YOUR-USERNAME.github.io/lazy-gains/`.

## Add it to your home screen

- **iPhone (Safari):** Share, then **Add to Home Screen**.
- **Android (Chrome):** Menu, then **Install app**.

## Good to know

- Ticked meals, basket, budget and weigh-ins are saved in your browser. Clearing site data erases them.
- Prices, meals and portions live in the `SHOP`, `MEALS`, `SNACKS` and `WEEK` lists at the top of the script in `index.html`.
- After editing files, change the `lazy-gains-v1` name in `sw.js` so phones pick up the update.
