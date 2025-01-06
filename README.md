

# Memory Shift

Memory Shift is a simple memory-based game where players must remember the position of flipped cards and guess the correct position after they flip back to letters. The game is built using C++ and SFML.

## How to Play
1. At the start of the game, several cards are displayed with images.
2. After 5 seconds, the cards flip over to show letters.
3. The player needs to guess the correct position of a randomly chosen card by navigating with arrow keys.
4. The player has 3 chances to make a correct guess. Each correct guess adds 10 points, and each wrong guess costs a life.

## Key Features
- 3x3 grid of cards
- Random card shuffling
- Score and lives tracking
- Highlighted selection for navigation
- Game over screen when lives reach zero

## Screenshots
![Game Start Screen](H:/harryy2ndlasttry/Start_screen.png)
![Screen_before_flipping](H:/harryy2ndlasttry/Screen_before_flipping.png)
![Screen_after_flipping](H:/harryy2ndlasttry/Screen_after_flipping.png)
![Game Over Screen](H:/harryy2ndlasttry/Game_over_screen.png)

## How to Run the Game

### Requirements
- SFML library
- C++ compiler (like g++ or MSVC)
- Image assets for the cards (in `.jpg` format)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/memory-shift.git
   ```
2. Navigate to the project directory:
   ```bash
   cd memory-shift
   ```
3. Compile the code:
   ```bash
   g++ main.cpp -o memory_shift -lsfml-graphics -lsfml-window -lsfml-system
   ```
4. Run the game:
   ```bash
   ./memory_shift
   ```

## Libraries Used
- [SFML](https://www.sfml-dev.org/) (Simple and Fast Multimedia Library) for graphics, window management, and events.

## Assets
- Background image: `bakground.jfif`
- Card images: `card1.jpg`, `card2.jpg`, ..., `card40.jpg`

Make sure you place all the images in the same directory as the executable.

---
