# Snake Rivals

Snake Rivals is a browser-based Snake variant built in a single HTML file. It keeps the classic food-and-growth loop, then adds rival AI snakes, bite-based combat, pickups, and configurable match rules.

## Run

Open `index.html` in a browser.

## Controls

- Move with Arrow Keys or WASD.
- On mobile, use the on-screen direction buttons.
- Press Space to start, pause, or resume.
- Press R to restart.
- Use the Full Screen button for canvas-only fullscreen play.

## Gameplay

- Rival snakes: AI snakes spawn during play and compete for food, pickups, and space.
- Bite rules: snakes can attack heads or bite bodies, with selectable combat rules.
- Speed pickups: temporary speed boosts appear on the board.
- Configurable arena: change width, height, cell size, wall behavior, colors, and grid visibility.
- Game options: tune player speed, AI speed, AI difficulty, bite growth, and rival-snake behavior.
- Persistent high score: the best score is saved locally in the browser with `localStorage`.

## Options

- `Wall kills`: toggles between wall death and wraparound movement.
- `AI mode`: chooses easier wandering behavior or more aggressive tactical movement.
- `Bite rule`: selects safe-zone bite logic or simpler body-bite rules.
- `Bite growth`: chooses whether bites grow by `+1` or by the number of eaten segments.
