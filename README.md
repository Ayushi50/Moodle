# Moodle — the mood-reading game

**▶ Play it live: https://moodle-jade.vercel.app/**

A single-file party and couples game about reading each other's moods. Pass one phone around, guess how the other person would honestly feel, play quick skill rounds, and find out your couple type — or which team wins the night.

## Play

Open **https://moodle-jade.vercel.app/** on any phone or laptop — nothing to install. Best on a phone: pass it around the room.

Prefer offline? Download `index.html` and open it in any modern browser. No build step, no server.

## Run locally

```bash
git clone https://github.com/Ayushi50/Moodle.git
cd Moodle
open index.html        # or just double-click it
```

## Deploy

The repo is a static site, so any static host works. It's deployed on Vercel from the `main` branch (framework preset: *Other*, no build command, output root `/`). Pushing to `main` redeploys automatically.

## Modes

- **Couple** — 2 players, 10 rounds, one shared score. Ends with your couple type.
- **Party** — 2 teams, 12 rounds, head-to-head scoring. Ends with a winner.

## Rounds

| Round | What happens |
| --- | --- |
| Mood reading | One player secretly picks how they'd honestly feel about a situation. The other side gets two guesses (3 pts first try, 1 pt second). |
| Memory | Match six pairs of mood cards in 45 seconds. |
| Reflex | Two players tap when the marker crosses a shrinking zone. |
| Sequence | Watch a sequence of moods, then repeat it as it grows. |
| Performance | Act out a dare; the other side scores it 1–3. |
| Finale | Both sides secretly pick their own mood — match for bonus points. |

## Themes

Eight editions, each with its own characters, scenarios, dares, mood names and look:

Anime · Bollywood · Hollywood · Kitty Party · Gen Z · Millennial · Corporate · College

## Tech

- Plain HTML, CSS and JavaScript in one file — no frameworks or dependencies
- Characters are hand-built SVG line-art illustrations
- Fonts load from Google Fonts
- Best score is saved in the browser's local storage


## Project structure

```
Moodle/
├── index.html            # the entire game: markup, styles, data and logic
├── favicon.svg           # browser tab icon
├── apple-touch-icon.png  # home-screen icon (iOS)
└── README.md
```

## Customising

Everything lives in `index.html`:

- `THEMES` — add or edit editions (characters, mood names, scenarios, dares, result tiers)
- `PLANS` — change round counts and the round order for couple and party modes
- `STY` — per-theme accent colours and display fonts

## Notes

The name overlaps with the Moodle education platform. Fine for parties and personal use; consider a variant like "Moodl" if you ever publish it more widely.
