Black Jack


# Blackjack Game in Python

A classic Blackjack card game built using Python and Pygame. The project features a graphical interface, card dealing, player decisions, dealer gameplay, score calculation, and win/loss tracking.

## Features

- Graphical user interface built with Pygame.
- Four standard decks of playing cards.
- Random card dealing.
- Player actions:
  - Hit: Draw another card.
  - Stand: End the player's turn.
- Automatic card score calculation.
- Ace handling (1 or 11 points).
- Dealer draws cards until reaching at least 17.
- Win, loss, and draw detection.
- Session-based win/loss/draw statistics.
- Interactive buttons for dealing and restarting games.

## Technologies Used

- Python
- Pygame
- Random
- Copy

## Game Rules

1. The player and dealer are each dealt two cards.
2. The player can choose to Hit or Stand.
3. The objective is to get a hand value as close to 21 as possible without exceeding it.
4. Number cards retain their face value.
5. Jack, Queen, King, and 10 are worth 10 points.
6. Aces are worth either 1 or 11 points, depending on the hand.
7. Once the player stands, the dealer reveals the hidden card.
8. The dealer continues drawing cards until reaching a score of at least 17.
9. The winner is determined by comparing both scores.

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Blackjack-Python.git
```

### 2. Navigate to the project directory

```bash
cd Blackjack-Python
```

### 3. Install dependencies

```bash
pip install pygame
```

### 4. Run the game

```bash
python main.py
```

## Controls

| Action | Control |
|---|---|
| Deal Hand | Click DEAL HAND |
| Draw Card | Click HIT ME |
| End Turn | Click STAND |
| Restart | Click NEW HAND |
| Exit Game | Close the window |

## Project Structure

```text
Blackjack-Python/
│
├── main.py
└── README.md
```

## Game Interface

The game runs in a 600 × 700 Pygame window with separate sections for the dealer's cards, player's cards, scores, and interactive controls.

## Future Improvements

- Add card images and animations.
- Implement proper Blackjack payouts.
- Add betting and virtual currency.
- Add card counting mechanics.
- Improve game logic for Blackjack natural hands.
- Add sound effects and background music.

## Author

Developed as a Python game development project using Pygame.

---

**Note:** This project is intended for learning Python, game development, and basic game logic.



FLOW OF THE PROJECT

![alt text](mermaid-diagram.png)


