# Tic-Tac-Toe (Console Game)

A classic two-player, command-line Tic-Tac-Toe game written in Python 3. Players take turns choosing positions on a 3x3 grid until one player wins or the game ends in a draw.

---

##  Features

- **Interactive 3x3 Grid:** Visualizes position numbers (1–9) for empty cells so players know where to move.
- **Input Validation:** Prevents invalid inputs (letters, out-of-bounds numbers, or taking an already occupied position).
- **Automatic Win & Draw Detection:** Checks all 8 winning lines (rows, columns, diagonals) after every turn and detects full board conditions.
- **Replay Support:** Allows players to play multiple rounds in a row.
- **Graceful Exit:** Safe handling for keyboard interrupts (`Ctrl + C`) and automated inputs (`EOFError`).

---

## How to Play

1. **Board Layout:** Positions are numbered 1 to 9:
   ```text
    1 | 2 | 3
   ---+---+---
    4 | 5 | 6
   ---+---+---
    7 | 8 | 9
