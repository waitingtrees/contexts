# Contexts

A floating-blob todo app, installable on iPhone as a home-screen web app (PWA).

- Open the GitHub Pages URL in **Safari** on your phone
- Tap **Share → Add to Home Screen**
- Launches full-screen, works offline, todos persist on-device (localStorage)

Self-contained: `index.html` has all JS/CSS/fonts inlined. `sw.js` caches the shell
for offline use; `manifest.webmanifest` + icons make it installable.

To update the app, replace `index.html` and bump the cache version in `sw.js`.
