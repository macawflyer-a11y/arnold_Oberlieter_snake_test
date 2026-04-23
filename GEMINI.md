# GEMINI.md - Project Context

This file provides instructional context for AI agents working on this project.

## Project Overview

A classic, simple Snake game developed in Python using the `pygame` library. The project is designed as a lightweight prototype with a focus on readability and ease of setup.

- **Primary Language**: Python 3.9+
- **Key Library**: `pygame`
- **Architecture**: Single-script game loop handling input, state updates, and rendering.

## Building and Running

### Prerequisites
- Python 3.x
- pip

### Setup
1. (Optional) Create a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```
2. Install dependencies:
   ```bash
   python3 -m pip install -r requirements.txt
   ```

### Running the Game
```bash
python3 snake_game.py
```

### Testing
- Currently, there are no automated tests. Manual verification involves running the game and checking:
    - Snake movement via arrow keys.
    - Growth upon eating food.
    - Collision detection (walls and self).
    - Game over/restart logic.

## Development Conventions

- **Code Style**: Simple, procedural style. Follows PEP 8 where possible, but prioritizes clarity for a single-file script.
- **Naming**: Snake case for variables and functions (e.g., `game_loop`, `snake_List`).
- **State Management**: Game state is managed via local variables within the `gameLoop` function.
- **Rendering**: Uses Pygame's `draw.rect` for both the snake and food.
- **Input Handling**: Uses `pygame.event.get()` to capture keyboard events in the main loop.
