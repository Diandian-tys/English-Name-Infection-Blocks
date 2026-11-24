# Infection Blocks

A Minecraft Bedrock Edition addon that introduces a deadly spreading infection.

When you first spawn in the world, an **Infection Block** appears under your feet. After a short 3-second countdown, the infection begins to spread, converting nearby blocks into more infection blocks. The infection is unbreakable, instantly kills any entity that steps on it, and grows faster every time a mob or player dies on it.

## Features

- Infection block appears under the player on first spawn
- 3-second countdown before the infection starts spreading
- Infection blocks cannot be mined or destroyed by explosions
- Continuously spreads to adjacent blocks
- Any entity (players or mobs) that steps on an infection block dies instantly
- Deaths on infection blocks increase the infection’s energy, making it spread faster
- Simple and performance-conscious spreading system

## Installation

1. Download the `.mcaddon` file from the Releases page
2. Open it with Minecraft (Bedrock)
3. Enable both the **Behavior Pack** and **Resource Pack** in your world settings
4. Create a new world or load an existing one (recommended to test in a new world first)

## How it works

1. On your first spawn, an infection block is placed beneath you
2. A countdown (3 → 2 → 1) appears on screen
3. After the countdown, the infection begins converting nearby blocks
4. Stepping on any infection block kills the entity immediately
5. Each death that occurs on an infection block increases the global energy multiplier, accelerating further spread

## Notes

- The infection prioritizes converting existing blocks rather than filling air
- Spread speed is limited for performance and has a maximum energy cap
- Recommended for testing in Creative or a dedicated test world

## Credits

Created for Minecraft Bedrock Edition.

## License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.
