
# Matchmaker Game 🎮

This is a simple **Memory Matchmaking Game** built using Python and the Tkinter library. The game displays a grid of buttons, each hiding a symbol. Players click on buttons to reveal their symbols, trying to find matching pairs. When all pairs are matched, the game is complete!

## Features
- **Interactive Gameplay**: Players reveal symbols by clicking on the buttons.
- **Randomized Symbols**: Each game shuffles the symbols to ensure a unique experience every time.
- **Simple UI**: Built with Tkinter, the interface is clean and functional.
  
## Requirements
To run this program, you'll need:
- Python 3.x installed on your system.
- Tkinter library (comes pre-installed with Python).

## How to Run
1. Clone or download this repository:
   ```bash
   git clone https://github.com/Abhilashchary/matchmaker-game.git
   cd matchmaker-game
   ```
2. Run the Python script:
   ```bash
   python matchmaker.py
   ```
3. The game window will open. Start matching pairs of symbols!

## How to Play
1. Click on any button to reveal the hidden symbol.
2. Click on a second button to reveal its symbol.
3. If the symbols match, the buttons are disabled.
4. If the symbols do not match, they will reset after a brief pause.
5. Continue until all pairs are matched.

## File Details
- `matchmaker.py`: The main Python file containing the game's logic and UI implementation.

## Customize the Game
You can adjust the game grid and symbols by editing these sections in the `matchmaker.py` file:
- **Symbols**: Add or remove Unicode symbols in the `symbols` list.
- **Grid Size**: Modify the grid size in the nested loop where buttons are created.

## Contribution
Feel free to fork the repository and submit pull requests for any enhancements or bug fixes.
