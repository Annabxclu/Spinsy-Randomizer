# Spinsy

Small choices, settled by chance. A single-page randomizer web app with no build step and no dependencies.

## Tools

- **Wheel** – keep a list of your own wheels: create, rename, copy and delete them. Each option gets a colour and a weight (1–10) that sets its slice size and chance. Seven ready-made wheels to start from, plus an option to remove the winner after each spin.
- **Coin** – 3D coin flip with a running heads/tails count.
- **Dice** – roll 1–6 dice, d4 to d20, with totals.
- **Number** – pick one or many numbers from any range, with or without repeats, optionally sorted, with a Copy button.
- **Fingers** – everyone holds a finger on the screen and 1–3 winners are picked after 2 seconds. On a computer, click to place dots and press Pick now.

Randomness comes from `crypto.getRandomValues`. Wheels, settings and the last 8 results are saved in the browser's `localStorage`. Each tool has its own link: `#wheel`, `#coin`, `#dice`, `#number`, `#fingers`.

## Run it

Open `index.html` in a browser. To host it, turn on GitHub Pages for this repo (Settings → Pages → Deploy from branch → `main` / root).
