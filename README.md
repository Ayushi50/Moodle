# Moodle — the mood-reading game

A single-file party and couples game about reading each other's moods. Pass one phone around, guess how the other person would honestly feel, play quick skill rounds, and find out your couple type — or which team wins the night.

## Play

Open `index.html` in any modern browser (works great on a phone). No install, no build step, no server.

To host it for free, enable **GitHub Pages** on this repo (Settings → Pages → Deploy from branch → `main` / root). The game will be live at `https://<username>.github.io/moodle/`.

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
