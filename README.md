# Arkade

A single-file arcade. Open `index.html` in a browser and play. No install, no account, no server.

Scores, favorites, themes, and unfinished games stay on this device.

## Play

1. Double-click `index.html`, or drag it into Chrome, Firefox, Safari, or Edge.
2. Press **Play Now** to open the library, or **Press start.** to jump into a random game.
3. **Tonight** picks one game for the day.
4. Each game opens with a short how-to. Press Start playing, or Enter, to begin.

## Same device, two players

Multiplayer is local. Both people use one keyboard and one screen. It is not online.

Player 1 uses **WASD**. Player 2 uses the **arrow keys**.

| Game | Together |
| --- | --- |
| Snake | Two snakes. Last one standing wins. |
| Pong | Left paddle vs right paddle. First to 7. |
| Breakout | Two paddles, one ball, shared lives. |
| Flappy Bird | Two birds, same pipes. |
| Space Shooter | Co-op. Shared score. |
| Neon Racer | Two cars, one road. |
| Pixel Runner | Race on one screen. |

Tic Tac Toe is different. **Friend** means take turns on the same device. Player 1 is X, Player 2 is O. It is not WASD versus arrows.

## Controls

| Key | What it does |
| --- | --- |
| Enter or Space | Start from the how-to |
| P | Pause |
| Esc | Save a resume and leave |
| Ctrl or Cmd + Z | Undo the last move |
| ? | Open how to play again |
| T | Cycle themes |
| / | Jump to search |
| F | Fullscreen, from the in-game button |

A gamepad works too: stick to move, A to act, Start to pause.

On a phone, the on-screen pad appears under the game.

## The cabinet

The hero machine is a tiny demo, not a saved score.

- Drag the stick, or tap it, to move.
- Red chomps. Green uses the armed power-up. Cyan plays the game named on the screen.
- **High Scores** lists bests on this device. Tap a row to play.
- **Power Ups** arms Swift, Shield, or Magnet for that demo. The green button uses it for 8 seconds. Arkanoid is the game that drops real power-ups.
- **Achievements** unlock from how you play here.

## Library

Search, filter by category, or sort by new, cabinet order, A–Z, most played, or best score.

Cards show your best score and how many times you have played. **Continue** appears when a game was left mid-run.

## Themes

Open the moon button, or press **T**.

Neon Night, Daylight, Synthwave, Matrix, Deep Ocean, Magma, Galaxy, Cherry Night, Frostbyte, Amber CRT, Coin-op, and Red Noir.

Each theme has its own colors, background motion, and switch sound. Particles and UI sounds can be turned off in that panel. Music, volume, motion, and text size are in Settings.

## What is saved

Everything uses `localStorage` in the browser. Nothing is uploaded.

- Best score for each game, level, and 1P or 2P
- Favorites and recently played
- A resume save, so Esc can pick up later
- Theme, music, and the other settings

Clear best scores or resume saves from Settings. Reset does not remove favorites.

## Games

28 originals, inspired by classic play. No ROMs and no external art files.

Snake, Tetris, Pong, Breakout, Flappy Bird, Space Shooter, Minesweeper, Tic Tac Toe, Memory Card, Sudoku, 2048, Pac-Maze, Arkanoid, Neon Racer, Pixel Runner, Chess, Checkers, Connect Four, Simon, Whack-a-Mole, Asteroids, Dino Run, Tower of Hanoi, Hangman, Slide Puzzle, Neon Stack, Orbit Flip, and Bubble Pop.

Breakout is the plain brick game, and it has co-op. Arkanoid is solo, with a denser wall and falling icons: a wider paddle, a slower ball, or an extra life.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The whole arcade: pages, games, sound, and themes |
| `README.md` | This note |
