# Word Zap

A spelling and typing game for kids. Captain Cubby the teddy bear flies his starship from Mercury to Neptune, and asteroids with pictures on them come flying at the windscreen. Type the word for each picture and Cubby's turret zaps it before it hits the ship.

**Play it:** https://teddybearhero.github.io/word-zap/

## How to play

1. Captain Cubby explains the game on the front screen. Tap **Next** to hear each step.
2. Pick a planet. Each planet is a level, and each level has longer words.
3. Type the word for the picture on each asteroid. Wrong letters are ignored, so mistakes never pile up.
4. If an asteroid gets through, the ship loses a shield. You have five.
5. The closer you get to the planet, the faster the asteroids fly.

| Planet  | Words        | Asteroids at once |
|---------|--------------|-------------------|
| Mercury | 3 letters    | 1 |
| Venus   | 4 letters    | 1 |
| Earth   | 5 letters    | 1 |
| Mars    | 6 letters    | 2 |
| Jupiter | 7 letters    | 2 |
| Saturn  | 8 letters    | 2 |
| Uranus  | 9 letters    | 3 (2 on phones) |
| Neptune | 10+ letters  | 3 (2 on phones) |

## About the game

- One file, `index.html`, with no build step and nothing to install.
- Works on phones, tablets and computers in any modern browser.
- No ads, no accounts, and no data collected. Progress (stars per planet) is kept only in the player's own browser.
- Captain Cubby's voice uses the device's built-in text-to-speech, so it sounds slightly different on each device. Turn it off with **Say words out loud**.

## Changing the game

All the settings are near the top of the script in `index.html`:

- `LEVELS` holds each planet's words and pictures. Add or swap words there.
- `PER_LEVEL` sets how many asteroids each trip has (default 10).
- `TOP_SPEED` sets how much faster the last asteroid is than the first (default 2.2×).
- `MAX_HP` sets the number of shields (default 5).
