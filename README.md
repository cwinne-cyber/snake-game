# Retro Toxic Snake

A Nokia-inspired Snake game with colourful pixel-art food, funny reactions, retro sounds and a deadly biohazard. Built with HTML5 Canvas, CSS and vanilla JavaScript. No installation, dependencies or server required.

## Play

Open `index.html` in a modern browser and click **START GAME**. The game works offline because the sprites are embedded and sounds are synthesized using the Web Audio API.

## Controls

| Input | Action |
| --- | --- |
| Arrow keys / WASD / 2, 4, 8, 6 | Move |
| Swipe on the board | Move on touch devices |
| Space | Pause or resume |
| Restart | Start a new game |
| Sound | Toggle audio |

## Food and hazards

| Item | Effect | Reaction |
| --- | --- | --- |
| Broccoli | +1 length, +10 points | Happy face and chime |
| Headphone smiley | +1 length, +10 points | Hearts and cheerful melody |
| Orange-face parody | −1 length, −10 points | Puking animation and sound |
| COVID-19 virus | −1 length, −10 points | Purple face and burp |
| Biohazard | Instant game over | Green slime drips over the screen |

Score cannot fall below zero. Food positions are randomized after eating. The snake accelerates as the score rises. Hitting a wall, biting yourself or losing your last segment ends the game. A four-note descending sad-trombone-style sound plays on defeat. High scores are stored locally when browser storage is available.

## Project structure

- `index.html` — complete game, embedded images, styles, logic and synthesized audio.
- `README.md` — instructions and project description.

## Publish with GitHub Pages

Upload both files to a GitHub repository. In **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save. A public repository and Pages site should only be used once you have permission to redistribute the included images.

## Image credits and rights

The game includes user-supplied images, some bearing stock-image watermarks. Their original rights remain with their respective owners. Redistribution rights have not been verified; replace or license these assets before public distribution. No open-source license is asserted for the images. The game is an independent retro-inspired project, not an official Nokia product.

## Testing

JavaScript syntax checked; interactive gameplay and audio have not been verified in Safari.
