# Conway's Game of Life

<p>
  <a href="https://technikweber.github.io/conways-game-of-life/"><img alt="Live demo" src="https://img.shields.io/badge/live%20demo-open-brightgreen"></a>
  <img alt="Runs in the browser" src="https://img.shields.io/badge/runs%20in-the%20browser-blue">
  <img alt="UI language: German" src="https://img.shields.io/badge/UI-Deutsch-informational">
  <a href="LICENSE"><img alt="License: MIT" src="https://img.shields.io/badge/license-MIT-green"></a>
</p>

An interactive browser version of John Conway's famous cellular automaton — plain
HTML, CSS and JavaScript in a single file.

👉 **[Try it](https://technikweber.github.io/conways-game-of-life/)** ·
**[Extended version](https://technikweber.github.io/conways-game-of-life/conways_game_of_life_extended.html)**

## What is the Game of Life?

Not a game in the usual sense, but a cellular automaton: a grid of cells that are either
*alive* or *dead*. A few simple rules produce astonishingly complex patterns — gliders,
oscillators, whole "machines" that build new ones.

## The rules

In every generation, each cell's fate is decided by its eight neighbours:

1. **Underpopulation:** a live cell with fewer than 2 live neighbours dies.
2. **Survival:** a live cell with 2 or 3 live neighbours lives on.
3. **Overpopulation:** a live cell with more than 3 live neighbours dies.
4. **Reproduction:** a dead cell with exactly 3 live neighbours comes alive.

## Features

- Click cells to set or clear them
- Start/pause, single step, clear, random fill
- Adjustable speed and cell size, grid on/off
- Six colour schemes
- Ten classic patterns to place: glider, blinker, toad, beacon, pulsar,
  pentadecathlon, Gosper glider gun, acorn, R-pentomino, diehard
- Generation and population counters

The **extended version** adds full screen, stepping back and forward in time, a
statistics graph, drawing modes (pen, brush, spray, wave), painting while dragging and
symmetry modes (mirrored, 4- and 8-fold radial).

The interface is in German.

## Run it locally

Pure front end — clone and open the file in a browser:

```bash
git clone https://github.com/TechnikWeber/conways-game-of-life.git
```

Then open `index.html` (or `conways_game_of_life_extended.html`).

## License

[MIT](LICENSE).
