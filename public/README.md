# Match the Avatar

**Match the Avatar** is a fun and interactive memory game where players flip cards to find matching avatars. The avatars are dynamically generated using the [DiceBear API](https://dicebear.com/), ensuring each match features a unique, pixel-art-style avatar from Harry Potter characters.

## Features

- **Dynamic Avatar Generation:** Avatars are generated using DiceBear's API based on the names of Harry Potter characters.
- **Responsive Design:** The grid adapts to different screen sizes.
- **Score and Timer:** The game tracks the player's score and elapsed time.
- **Restart Functionality:** Players can restart the game at any time.
- **Animated Cards:** The cards gently "float" using CSS animations for a more magical feel.

## How to Play

1. Start by clicking on a card to flip it.
2. Match two cards with the same avatar to score points.
3. Every successful match awards 10 points. A mismatch subtracts 1 point.
4. Continue matching all cards in the shortest time possible.
5. Once all pairs are matched, the game ends, and your final score is displayed.

## Live Preview

To play the game locally:

1. Clone or download the repository.
2. Open the `index.html` file in your browser.

## Files

- `index.html`: The main HTML file containing the game structure and logic.
- `style`: The inline CSS styling to ensure responsiveness and design consistency.
- `script`: The JavaScript functionality for game logic, including shuffling, card flipping, and avatar generation.

## Game Components

- **HTML Structure**: The game board consists of a 6x6 grid (or responsive down to smaller grids for mobile devices) of cards.
- **CSS Styling**: The game uses flexbox and grid for layout, along with media queries to adapt to different screen sizes.
- **JavaScript Logic**:
  - Cards are dynamically generated and shuffled at the start.
  - Clicking on a card flips it and checks for a match.
  - The score and timer are updated as the game progresses.

## DiceBear API

Avatars are fetched dynamically for each Harry Potter character using the DiceBear API. Each character's name serves as a seed for generating a unique pixel-art avatar.

Example URL used for the avatars:

## How to Customize

1. **Change Characters**: You can modify the array of `characters` in the JavaScript to include any other names you prefer.
   ```javascript
   const characters = [
     'Harry', 'Hermione', 'Ron', 'Dumbledore', 'Snape', 'Draco',
     
   ];
