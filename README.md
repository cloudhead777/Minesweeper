# 🧩 Minesweeper

A simple implementation of the classic **Minesweeper** game. The player must clear a board containing hidden mines without detonating any, using numerical clues to deduce the locations of mines.

---

## Features
- Configurable grid size and number of mines.
- Classic Minesweeper rules:
  - Numbers indicate how many mines are adjacent to that cell.
  - Right-click (or alternate control) to flag potential mines.
  - Win by clearing all non-mine cells.
- Game over if you step on a mine.
- Optional timer to track completion speed.

---

## Getting Started

1. **Clone the Repository:**
```bash
git clone https://github.com/<your-username>/minesweeper.git
cd minesweeper
```
2. **Run the Game:**
   ```bash
   python minesweeper.py
   ```
⚙️ Controls

Left Click → Reveal a cell

Right Click → Flag or unflag a mine

Numbered Cell → Shows how many mines are in the 8 surrounding cells

Empty Cell → Automatically reveals nearby safe cells

🏆 Winning & Losing

Win → Reveal all safe cells, with all mines either flagged or avoided

Lose → Reveal a mine

📂 Project Structure
minesweeper/
├── minesweeper.py   # Main game file
├── assets/          # (Optional) images, icons, or sounds
├── README.md        # Project documentation
└── LICENSE          # (Optional) license file


