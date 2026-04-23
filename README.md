# Simple Snake Game

A classic Snake game built with Python and Pygame.

## Prerequisites

- Python 3.x installed on your system.
- `pip` (Python package installer).

## Installation

1. (Optional) Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## How to Play

Run the game using the following command:
```bash
python snake_game.py
```

### Controls
- **Arrow Keys**: Move the snake (Up, Down, Left, Right).
- **Q**: Quit the game when you lose.
- **C**: Play again when you lose.

### Rules
- Eat the green food blocks to grow and increase your score.
- Avoid hitting the walls or the snake's own body.
- The game ends if you collide with a wall or yourself.
