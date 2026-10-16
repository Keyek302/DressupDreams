# Dress-Up Dreams

A mobile-friendly dress-up game made for four sisters (ages 3, 4, 9 and 13). No ads, no paywalls, no accounts. Everything is a single `index.html` file.

## Features
- 4 original characters, each with her own starting style
- Dresses, non-dress outfits (tees, jackets, hoodies, overalls, jumpsuit, track suit), hair, crowns, shoes, extras, makeup, textures, face and eye options
- Pet sidekicks (bunny, kitten, dragon, puppy) that react when tapped
- Drag-and-drop stickers with a trash can to remove them
- Tap reactions (giggle, twirl, hop) and swipe-to-browse styles
- Gems earned in minigames unlock locked pieces: Sparkle Catch, Memory Match, Tic Tac Toe, Color Match, Pattern Magic, Lucky Spin (every 20 minutes) and a daily gift
- Save outfits to a gallery; progress, gems and unlocks save automatically in the browser (localStorage)

## Play locally
Open `index.html` in any modern browser.

## Host on GitHub Pages
1. Create a new repo (for example `DressUpDreams`) and upload `index.html` and `README.md`.
2. Go to **Settings > Pages**, set the source to **Deploy from a branch**, choose `main` and `/ (root)`, then save.
3. After a minute the game is live at `https://<your-username>.github.io/DressUpDreams/`.

## Notes
- Saves are stored per device and browser, so each girl's progress stays on the device she plays on.
- The only outside resource is the Fredoka font from Google Fonts. The game falls back to a system font offline.
