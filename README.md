# Blackjack Game

## Description
This project is a digital version of the classic card game **Blackjack**, implemented in Python using the Pygame library. The game features an interactive graphical interface, dynamic card rendering, and simple controls, making it engaging and easy to play.

---

## Features
- **Interactive Gameplay**: Players can hit, stand, and play against a dealer.
- **Graphical Interface**: A casino-themed background, card images, and animations enhance the user experience.
- **Dynamic Scoring**: Real-time score calculation based on the player's and dealer's hands.
- **Game Instructions**: A dedicated instructions screen guides new players.
- **Play Again Option**: Restart the game after each round without relaunching.
- **Sound Effects**: Background music to enhance the immersive experience (if the `casino_music.mp3` file is available).

---

## Installation

1. Clone the repository or download the source code.
2. Ensure you have Python installed (version 3.7 or above).
3. Install the required Pygame library by running:
   ```bash
   pip install pygame
   ```
4. Place the following assets in the correct directories:
   - **Background Image**: `casino_background.jpg`
   - **Card Images**: Inside a `cards` folder, named in the format `<value>_of_<suit>.png` (e.g., `2_of_hearts.png`).
   - **Music File**: `casino_music.mp3`.
5. Run the game:
   ```bash
   python blackjack_game.py
   ```

---

## Controls
- **`H` Key**: Hit (draw a new card).
- **`S` Key**: Stand (end your turn).
- **Mouse Click**: Interact with buttons on the instructions and game-over screens.

---

## Gameplay Rules
1. The objective is to get as close to 21 as possible without exceeding it.
2. Number cards are worth their face value.
3. Face cards (Jack, Queen, King) are worth 10 points.
4. Aces can be worth 1 or 11 points, whichever benefits the player.
5. The dealer must stand on a score of 17 or higher.
6. If either the player or dealer exceeds 21, they "bust," and the other wins.
7. A tie occurs if both have the same score.

---

## Screens

### 1. **Instructions Screen**
- Displays the rules and controls of the game.
- Includes a "Play Now" button to start the game.

### 2. **Game Screen**
- Displays the player’s and dealer’s cards.
- Real-time score updates for the player.

### 3. **Game Over Screen**
- Shows the winner (Player, Dealer, or Tie).
- Includes a "Play Again" button to restart the game.

---

## File Structure
```
blackjack_game/
|— blackjack_game.py            # Main game script
|— cards/                      # Folder containing card images
|    |— 2_of_hearts.png
|    |— ...
|— casino_background.jpg        # Background image
|— casino_music.mp3             # Background music file
```

---

## Customization
- **Card Images**: Add your custom card designs by replacing the images in the `cards` folder.
- **Background Music**: Replace `casino_music.mp3` with your preferred music.
- **Screen Dimensions**: Modify `SCREEN_WIDTH` and `SCREEN_HEIGHT` in the script for different screen sizes.

---

## Troubleshooting
- **Error Loading Images**: Ensure all card images are correctly named and stored in the `cards` folder.
- **No Sound**: Verify that `casino_music.mp3` exists in the same directory as the script.
- **Missing Pygame Library**: Install it using the command `pip install pygame`.

---

## Credits
- **Programming**: Abdul Rehman Marfani
- **Assets**:
  - Card Images: Custom or sourced appropriately.
  - Background Music: `casino_music.mp3` (ensure copyright compliance).

---

## License
This project is open-source and free to use under the MIT License. Feel free to modify and distribute it as you wish.

---

Enjoy playing Blackjack!

