# Lavender Hours — iPad Home Screen setup

This is a small standalone study timer with Pomodoro, custom countdown, stopwatch, breaks, and daily study tracking.

## Important
To install it as a proper Home Screen web app on iPad, the files must be hosted on an HTTPS website. This ZIP does not publish the site for you.

## Easiest route: GitHub Pages
1. On a computer (or using GitHub's website), sign in to GitHub and create a new **public** repository named `lavender-hours`.
2. Upload all five files in this folder: `index.html`, `manifest.json`, `sw.js`, `icon-192.png`, `icon-512.png`.
3. In the repository, open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. Wait for GitHub Pages to publish. Your site address will look like `https://YOUR-USERNAME.github.io/lavender-hours/`.
6. Open that HTTPS address in **Safari on your iPad**.
7. Tap Share → **Add to Home Screen** → Add.

## Notes
- Study totals are stored locally in that browser on that device. Clearing Safari website data can erase them.
- Keep the site URL the same to keep the same local study history.
- Allow notifications when prompted if you want timer-completion notifications. iPad notification support depends on installing the web app to the Home Screen and iPadOS settings.
