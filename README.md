# 🎮 Tic-Tac-Toe Game in C++

A simple yet powerful console-based **Tic-Tac-Toe game** written in C++, featuring both:
- ✅ **Human vs Computer** mode using the **Minimax AI algorithm**
- ✅ **Human vs Human** mode for two players locally

---

## 📌 Features

- 🧠 **Unbeatable AI** using Minimax
- 👨‍👩‍👧‍👦 **Two-player support** (Human vs Human)
- 📋 Clean and intuitive board display
- 🎮 Move guide using cell numbers (1–9)
- 🔁 Replay option after each match
- ❌ Win detection and draw handling

---

## 🕹️ Game Instructions

- The board is a 3×3 grid numbered like this:



1 | 2 | 3
4 | 5 | 6
7 | 8 | 9

- Players choose a number to mark their move.
- `'X'` is the Human player (or Player 1).
- `'O'` is the Computer (in AI mode) or Player 2 (in Human vs Human mode).

---

## 🧠 Game Modes

At launch, you’ll be asked to select a game mode:

1. **Human vs Computer**
   - Choose if you want to start first.
   - Computer uses Minimax for optimal moves.

2. **Human vs Human**
   - Take turns entering positions as Player X and Player O.

---

## 🛠️ How to Compile & Run

### Compile:
```bash
g++ -o tictactoe main.cpp
