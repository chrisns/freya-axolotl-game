# Axolotl World

A browser game designed by Freya, age 7. Axolotls are her favourite animal.

Play it here: https://chrisns.github.io/freya-axolotl-game/

## How to play

Swim your axolotl through 11 levels of the reef.

- Dodge the poisonous seaweed and the glowing red fish.
- Collect green fish and crabs for points.
- Watch for the rare secret Tadpole. It is fast and hard to catch, but
  catching it skips 3 levels.
- Finish all 11 levels to win.

Move with the arrow keys, WASD, or the on-screen keypad. Both keyboard and
touch controls work at the same time.

## Features

- 11 levels with rising difficulty.
- A colour picker for the axolotl, with Freya's favourite colours: blue,
  purple, pink, and green.
- A trophy cabinet that stores a star for each level you finish, plus the
  fish and crabs you collected on that level. It is saved in the browser,
  so it stays after you close the tab.
- A big, bold, colour-cycling score screen at the end of the run.
- Original chiptune background music and sound effects, built with the
  Web Audio API. This is not a cover of a real song. It is an original
  tune made for this game.

## Run it locally

The game is a single HTML file with no build step and no dependencies.
Open `index.html` directly in a browser, or serve the folder with any
static file server, for example:

```
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Tech

Plain HTML, CSS, and JavaScript. Canvas 2D for rendering. The Web Audio
API for music and sound effects. No frameworks, no build tools.
