# Wordle Clone

A browser-based Wordle clone with a dark theme, animations, and daily word tracking. Single HTML file, zero build steps.

## What we're building

- 6x5 grid of tiles for guessing 5-letter words
- Daily word selection deterministic by day-of-year + year
- Letter evaluation: green (correct position), yellow (wrong position), gray (not in word)
- Duplicate letter handling: exact matches first, then yellows up to remaining count
- Tile flip animation on guess submission
- Bounce animation on win
- Row shake + toast on invalid word
- On-screen QWERTY keyboard with color state tracking
- Win/loss toasts with custom messages
- Stats modal: games played, win %, streaks, guess distribution
- Share to clipboard with emoji grid
- Help/info modal with "How to Play" examples
- Game state and stats persisted in localStorage, keyed by date

## Tech

- React + Babel standalone via CDN (no build step)
- Single index.html file
- Dark theme: #121213 background, white text
- Green: #538d4e, Yellow: #b59f3b, Gray: #3a3a3c

## Constraints

- No em dashes in comments or text
- Keep code clean and well-commented
- Playable on desktop browsers (Chrome, Firefox, Safari)
- Signature at bottom-right: "Created by Stonedhawk (Rahul)" in 11px, #565656
- No obscure words in the answer list
