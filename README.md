# 🎲 Pig Game

A classic two-player dice game built with vanilla JavaScript, HTML, and CSS. Race your opponent to 100 points. But don't roll a 1!

---

## 📖 How to Play

Pig is a turn-based dice game for two players. The goal is to be the first player to reach 100 points.

On your turn, you can:

- Roll the Dice — A random number between 1–6 is rolled and added to your _current score_.
- Hold — Your current score is banked into your _total score_ and the turn passes to your opponent.
- Watch out for a 1! — If you roll a 1, your entire current score is lost and the turn switches immediately.

The first player to reach or exceed 100 total points wins the game.

---

Controls

| Button       | Action                                    |
| ------------ | ----------------------------------------- |
| 🎲 Roll Dice | Roll the dice and add to current score    |
| 📥 Hold      | Bank your current score and end your turn |
| 🔄 New Game  | Reset the game and start over             |

## ⚙️ Game Logic Overview

The game is managed through four core state variables:

| Variable       | Description                                                                 |
| -------------- | --------------------------------------------------------------------------- |
| `scores`       | Array holding the total (banked) score for each player `[player0, player1]` |
| `currentScore` | The active player's unbanked score for the current turn                     |
| `activePlayer` | Index of the current player (`0` or `1`)                                    |
| `playing`      | Boolean flag — `false` once a winner is declared                            |

---

Built With

- HTML5 — Structure
- CSS3 — Styling and layout
- Vanilla JavaScript (ES6) — Game logic, DOM manipulation

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
