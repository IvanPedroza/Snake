# 🐍 Snake Game (Processing)

A classic Snake game built with the **Processing** environment, featuring a unique competitive twist.

[![Coverage](https://img.shields.io/badge/coverage-90%25-brightgreen)](#)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![PyTest](https://img.shields.io/badge/tests-PyTest-orange.svg)

## Game Overview

This version of the Snake Game introduces a strategic competitive twist:
- **Your snake** grows each time it consumes an apple.
- **Opponent snake** shrinks each time you eat an apple.

Collect apples to outgrow your opponent, forcing them to shrink and ultimately lose!

## Installation

### Prerequisites
- **Processing** ([Download here](https://processing.org/download/))
- **PyTest** (for running tests)

```bash
pip install pytest
```

### Setup

Clone or download this repository and open the files in Processing:

```bash
git clone https://github.com/IvanPedroza/Snake.git
```

Run the game by pressing the **Run** button in Processing (▶️).

## How to Play

- Use the arrow keys (**Up, Down, Left, Right**) to control your snake.
- Collect apples to **grow your snake** and shrink the opponent snake.
- Avoid collisions with walls, yourself, or the opponent.

### Objectives

- **Grow your snake:** Eating apples lengthens your snake and shrinks your opponent.
- **Outlast your opponent:** Survive collisions longer than the opponent.
- **Strategize:** Plan your moves carefully to maintain the advantage.

## Game Features
- **Real-time Score Display**
- **Game Over Screen:** Displays your final score upon collision.
- **Easy Replay:** Restart quickly using the Processing IDE.

## Testing and Coverage

Comprehensive tests are provided using PyTest, covering:

- Snake movement and logic
- Collision detection
- Apple spawning mechanics
- Scoring system accuracy

### Running Tests

Execute tests by running:

```bash
pytest
```

## Contributing

Contributions are welcome! Fork the repository, make your changes, and submit a pull request.

## License

This Snake Game in Processing is open-source and available under the [MIT License](https://github.com/IvanPedroza/Snake/blob/main/LICENSE.md). You can use, modify, and distribute it freely.

## Acknowledgments

Inspired by Nokia’s classic Snake game, built using the [Processing](https://processing.org/) programming environment.

Enjoy the game!

