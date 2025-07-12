# Tile Adventure Game

## Overview

Tile Adventure is a mobile-friendly, browser-based adventure game built with HTML, JavaScript, and Tailwind CSS. Players navigate a tile-based world map, encounter random D&D-style events, and manage a character with stats and an inventory system. The game features turn-based encounters with dice rolls influenced by character stats, an experience system for leveling up, and item collection.

## Features

- **Tile-Based Map**: Explore a grid of grass and forest tiles.
- **Random Encounters**: Face combat, traps, or NPC interactions with a 40% chance per move.
- **Character Stats**: Health, strength, speed, and charisma affect encounter outcomes via D20 rolls.
- **Inventory System**: Collect items like Health Potions, Swords, and Gold Coins.
- **Experience System**: Gain XP to level up, increasing stats and max health.
- **Mobile-Friendly**: Optimized for touch controls on mobile browsers.

## How to Play

1. Open `index.html` in a modern web browser, preferably on a mobile device.
2. Use the on-screen buttons (Up, Left, Right, Down) to move the red square (player) across the map.
3. Each move may trigger an encounter (combat, trap, or NPC). Choose to attempt or flee:
   - **Attempt**: Rolls a D20 modified by the relevant stat (strength, speed, or charisma).
   - **Success**: Gain 10 XP and a chance to find an item. At 20 XP per level, level up to boost stats.
   - **Failure**: Lose 2 health. If health reaches 0, the game restarts.
4. Monitor your stats and inventory above the map.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/nordmanc/TileAdventureGame.git
   ```

2. Navigate to the project folder:

   ```bash
   cd TileAdventureGame
   ```

3. Open `index.html` in a web browser.

## Hosting with GitHub Pages

To host the game online:

1. Go to the repository’s **Settings** on GitHub.
2. Under **Pages**, select the `main` branch and `/ (root)` folder, then save.
3. Access the game at `https://nordmanc.github.io/TileAdventureGame` after a few minutes.

## File Structure

- `index.html`: The main game file containing HTML, JavaScript, and Tailwind CSS.

## Requirements

- A modern web browser (e.g., Chrome, Safari, Firefox) with JavaScript enabled.
- No additional dependencies or server setup required.

## Contributing

Feel free to fork the repository, make improvements, and submit pull requests. Suggestions for new features, such as additional encounter types or items, are welcome!

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Credits

Developed by \nordmanc. Powered by Tailwind CSS for styling.
