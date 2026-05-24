# SCT_WD_3

# ✖️ Circle & Cross | Animated Tic-Tac-Toe 〇

A sleek, modern, and interactive take on the classic Tic-Tac-Toe game. Built with HTML, CSS, and Vanilla JavaScript, this project features a beautiful glassmorphism UI and a dynamic particle background that responds to mouse movements.

## ✨ Features

* **Two Game Modes:**
    * **👥 VS Human:** Play locally against a friend.
    * **🤖 VS Computer:** Play against an AI opponent that actively tries to win or block your moves.
* **Interactive Canvas Background:** A custom-built particle system floats in the background and elegantly repels/attracts to the user's cursor.
* **Glassmorphism UI:** A modern design using semi-transparent, blurred panels (`backdrop-filter`) for a premium look and feel.
* **Smart AI:** The computer opponent uses logic to find winning moves, block your winning moves, take the center, or take corners strategically.
* **Live Score Tracking:** Keeps track of X wins, O wins, and Ties during your session.
* **Winning Animations:** Highlights the winning row/column/diagonal with a glowing neon green effect.
* **Responsive Design:** Carefully crafted to look great on desktop, tablet, and mobile screens.

## 🛠️ Technologies Used

* **HTML5:** Semantic structure and layout.
* **CSS3:**
    * Grid for the game board layout.
    * Flexbox for overall alignment.
    * `backdrop-filter` for the glass effect.
    * Gradients, box-shadows, and text-shadows for depth and neon styling.
* **Vanilla JavaScript:**
    * **Game Logic:** Handles turn-taking, win/tie detection, and scorekeeping.
    * **AI Logic:** Determines the best move for the computer.
    * **Canvas API:** Renders and animates the interactive particle background (`#interactive-bg`).


## 📁 Project Structure

The entire application is contained within a single file for maximum portability:

* `index.html`: Contains the structural markup, an inline `<style>` block for all CSS, and a `<script>` block containing both the canvas animation logic and the Tic-Tac-Toe game logic.

## 🎮 How to Play

1.  Select your desired game mode at the top (VS Human or VS Computer).
2.  Click any empty cell on the 3x3 grid to place your mark (X always goes first).
3.  Get 3 of your marks in a row (horizontally, vertically, or diagonally) to win!
4.  Click "🔄 NEW MATCH" to clear the board and play again while keeping the score.
