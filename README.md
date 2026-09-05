# Hamburger Drill

A small browser trainer for memorizing item locations on a 7×7 grid.

## What it does

- Builds a 7×7 board.
- Leaves 13 fixed cells empty.
- Randomly places four sets of nine ingredients on the remaining 36 cells.
- Quizzes you on one ingredient at a time.

## Ingredients

tomate, ketchup, moutarde, cornichon, oignon, fromage, galette, laitue, pain

## Empty cells

A1, A7, C3, C4, C5, D3, D4, D5, E3, E4, E5, G1, G7

## How to use

1. Open `index.html` in a browser.
2. The current ingredient appears in caps at the top.
3. Click the cell where you think that ingredient is.
4. The cell flips to show what is really there.
5. After a short pause the result is applied and a new ingredient appears:
   - Correct: the cell becomes blank and is removed from the quiz.
   - Wrong: the cell flips back.
6. When the board is cleared, a new board is generated automatically.

## Controls

- **Nouvelle grille** — generate a fresh board.
- **Debug** — toggle all cell contents visible or hidden.
