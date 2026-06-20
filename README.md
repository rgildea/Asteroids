# Asteroids

A classic Asteroids clone built in Python with Pygame, following the [Boot.dev](https://boot.dev) curriculum.

## Gameplay

Pilot a spaceship through an asteroid field and destroy incoming rocks before they destroy you. Large asteroids split into smaller, faster fragments when shot — clear them all to survive.

- **Avoid** asteroids — one hit ends the game
- **Shoot** asteroids to split them into smaller pieces
- **Small asteroids** are destroyed completely when shot

## Controls

| Key | Action |
|-----|--------|
| `W` | Thrust forward |
| `S` | Thrust backward |
| `A` | Rotate left |
| `D` | Rotate right |
| `Space` | Shoot |

## Requirements

- Python 3.13+
- [uv](https://github.com/astral-sh/uv) (recommended) or pip

## Running the Game

**With uv (recommended):**
```bash
uv run main.py
```

**With pip:**
```bash
pip install pygame==2.6.1
python main.py
```

## Project Structure

| File | Description |
|------|-------------|
| `main.py` | Game loop and entry point |
| `player.py` | Player ship movement and shooting |
| `asteroid.py` | Asteroid behavior and splitting logic |
| `asteroidfield.py` | Asteroid spawning logic |
| `shot.py` | Projectile behavior |
| `circleshape.py` | Base class for circular game objects |
| `constants.py` | Tunable game parameters |
| `logger.py` | Game event and state logging |
