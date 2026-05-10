# Whack-a-Mole

This is a simple Whack-a-Mole game built with HTML, CSS, and jQuery.

## Game Overview

The game begins with a countdown from 3 to 0. When the countdown reaches zero, the screen shows `Start` and the game begins. A mole then appears in one of the 9 holes in the game area at random. The player can click the mole to whack it. If the mole is hit, it disappears and reappears after a short delay. If the player does not hit it in time, the mole disappears by itself and appears in another random hole later.

The player starts with 3 lives. Each missed mole reduces the player's life by 1, and the border color of the holes changes to show the current status:

- 3 lives: green
- 2 lives: yellow
- 1 life: red
- 0 lives: game over

## Features

- Countdown start screen
- Random mole appearance
- Click-to-whack interaction
- Automatic hide and reappear behavior
- Life counter and game over screen
- jQuery-based event handling and screen control

## Files

- `whackamole.html`: main game page containing the HTML, CSS, and JavaScript
- `README.md`: project documentation

## How to Run

1. Open `whackamole.html` in a web browser.
2. Wait for the countdown to finish.
3. Click the mole whenever it appears to score points and avoid losing lives.

## Technologies Used

- HTML5
- CSS3
- jQuery 3.7.1
- Google Fonts: Gloria Hallelujah

## Notes

This project also uses image assets such as the mole and grass background. If those image files are not placed in the same folder as the HTML file, the page may not display correctly.
