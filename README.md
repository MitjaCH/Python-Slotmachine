# Python Slotmachine Minigame

This Python script simulates a simple slot machine minigame. Players can set their bets, number of lines to bet on, and deposit money to play the game. The script generates random symbols in a grid-like slot machine and calculates winnings based on the aligned symbols.

## How to Use

1. **Setup**: Open the Python file in your preferred environment.
2. **Adjust Settings**: Modify the constants at the beginning of the script (`MAX_LINES`, `MAX_BET`, `MIN_BET`, `ROWS`, `COLS`, `symbol_count`, `symbol_value`) to suit your preferences.
3. **Run the Game**: Execute the script and follow the instructions on the console.
4. **Deposit**: Enter the amount you'd like to deposit to start playing.
5. **Place Bets**: Specify the number of lines to bet on and the bet amount per line within the allowed limits.
6. **Play the Game**: Press Enter to spin the slot machine and see the results.
7. **Quit**: Type 'q' and press Enter to exit the game.

## Functions Overview

- `deposit()`: Allows users to input the initial deposit amount.
- `get_number_of_lines()`: Prompts users to select the number of lines to bet on.
- `get_bet()`: Lets users choose the bet amount per line.
- `spin(balance)`: Initiates a round of the slot machine game based on the selected bet and lines, updating the balance accordingly.
- `main()`: Controls the flow of the game, allowing users to play multiple rounds until they decide to quit.

Feel free to explore and modify the code according to your preferences!

---
