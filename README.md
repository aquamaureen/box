# 📦 Capture the Box

*A complete implementation of the classic Dots and Boxes game in a single HTML file. Play anywhere, anytime, forever.*

---

## About the Game

Dots and Boxes is a timeless strategy game that's easy to learn but deeply engaging. This implementation brings the classic pencil-and-paper experience to your screen with smooth animations, smart AI opponents, and support for up to 6 players.

**What makes this special:** Everything you need is in one file. Download it once, and it's yours to keep. Play offline on your laptop during a flight, on your phone at the beach, or on your tablet with the kids. No subscriptions, no logins, no updates that break things—just the game, working exactly as it should.

---

## Features

* 🎮 **Play Your Way** – Solo against AI, pass-and-play with friends, or practice strategies
* 🤖 **Smart Opponents** – Three AI difficulty levels that actually challenge you
* 👥 **Multiplayer** – Up to 6 local players on one device
* 🎨 **Beautiful Themes** – Light, Dark, and Brutal (bold Neo-Brutalist aesthetic)
* 🌐 **Works Offline** – Play anywhere, internet or not

---

## Quick Start

### Option 1: Just Open It

1. Download `index.html`
2. Double-click to open in your browser
3. Start playing


### Option 2: Host It Yourself

```bash
# Use any static server
python -m http.server 8000

# or
npx serve
```

---

## How to Play

Connect dots to create lines. Complete a square's fourth side to claim it and score a point. Claiming a box earns you an extra turn—chain them together for big plays!

* Click between any two adjacent dots to draw a line
* Complete the fourth side of a square to claim it as yours
* **Bonus Turn** – Get another move every time you complete a box
* **Win** – Have the most boxes when the grid is full

---

## Technical Details

**Built with:**

* Vanilla JavaScript (no frameworks needed)
* Canvas API for smooth rendering
* CSS custom properties for easy theming
* `localStorage` for game persistence

**Browser support:** Any modern browser (Chrome, Firefox, Safari, Edge) from 2020 or newer, including mobile browsers.

---

## Themes

* **Light** – Warm and professional
* **Dark** – Easy on the eyes
* **Brutal** – Bold, colorful, unapologetically loud Neo-Brutalist design

---

## Customization

It's all in one file—feel free to make it your own! Common customizations:

* Adjust colors in the `:root` CSS variables
* Tweak AI difficulty in the `App.AI` object
* Add sound effects using the Web Audio API
* Create new themes by copying the `[data-theme]` CSS blocks

---

## Why One File?

This game is built with a simple philosophy: software should work for you, not the other way around.

When you download this file, you truly own it. It works offline. It doesn't phone home. It won't stop working because a server shut down or a company changed direction. It's software you can trust to just work, today and years from now.

This approach is about remembering what made the web great: simple, resilient, user-first experiences.

---

## Contributing

Want to improve the game? Here's how:

1. Fork the project
2. Make your changes to `index.html`
3. Submit a pull request

Please keep it as a **single file**—that's the point!

---

## Credits

Inspired by the classic Dots and Boxes game and built with love for simple, lasting software.

Influences include the Neo-Brutalism design movement, the indie web, and the belief that great experiences don't require complexity.

---

## License

**MIT License** – Use it, modify it, share it, make it yours.

> Download once. Play forever. It's that simple.
