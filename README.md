# 🐍 100 Days of Python Tracker

An interactive, responsive single‑page web app that helps Python learners track their progress through the classic “100 Days of Python” challenge. Inspired by the check‑off poster style, it enforces one click per day, with smart locks, penalties for gaps, and an eye‑catching modern UI.

---

## 🚀 Live Demo

> Coming soon on GitHub Pages / Netlify / Vercel

---

## 🔥 Key Features

* **100‑Day Grid:** Fluid CSS Grid adapts from mobile to desktop (4×25 → 10×10 layout).
* **Sequential Unlock:** You can only mark Day N after completing Day N − 1.
* **24‑Hour Lock:** After marking a day, the next day unlocks 24 hours later.
* **48‑Hour Penalty:** If you skip two days (48 hours), the last three completed days are automatically erased to keep you motivated.
* **No Double‑Clicks:** Completed days cannot be clicked again.
* **Progress Persistence:** Uses `localStorage` for offline‑ready tracking, even across page reloads.
* **Dark/Light Theme:** Toggle button to switch themes; preference saved in browser.
* **Reset Control:** One‑click “Reset Progress” button (with confirmation) to start over.
* **Modern UI:** Smooth hover/press animations, checkmark badges, terminal‑style color palette.
* **Accessibility:** ARIA labels, focus styles, and high‑contrast mode for inclusive design.
* **PWA Basics:** Includes `manifest.json` and service worker (`sw.js`) for offline support and install prompt.

---

## 🤝 Contributing

Contributions are welcome! To propose changes:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/YourFeature`
3. Commit your changes: `git commit -m "Add YourFeature description"`
4. Push to branch: `git push origin feature/YourFeature`
5. Open a Pull Request, describing your improvement.

---

*Built with ❤️ for Python learners!*
