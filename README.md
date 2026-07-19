# 🏏 Bat Ball Stump Game

A modern, interactive, web-based game inspired by the classic Rock-Paper-Scissors, but with a cricketing twist! Play against the computer by choosing either **Bat**, **Ball**, or **Stump**.

## ✨ Features

- **Modern UI**: Features a beautiful glassmorphism design with gradient backgrounds and smooth hover animations.
- **Score Tracking**: Keeps track of your Wins, Losses, and Ties.
- **Persistent Storage**: Your score is saved in the browser's `localStorage`, so you can close the page and come back later without losing your progress.
- **Dynamic Feedback**: Visual color-coded feedback immediately tells you if you've won, lost, or tied the round.
- **Responsive**: Fully playable on both desktop and mobile devices.

## 🎮 How to Play

1. Open `index.html` in your web browser.
2. You will see three interactive icons: **Bat**, **Ball**, and **Stump**.
3. Click on your choice to play against the computer.
4. The result board will dynamically update to show your choice, the computer's choice, and the outcome of the match.
5. Your score will automatically update on the scoreboard below. You can reset it anytime using the **Reset Score** button.

## 📜 Rules of the Game

The rules are simple and follow a circular logic just like Rock-Paper-Scissors:

- **Bat beats Ball**: The batsman hits the ball! (Bat wins)
- **Ball beats Stump**: The bowler bowls out the stumps! (Ball wins)
- **Stump beats Bat**: The batsman is stumped out! (Stump wins)
- **Same choices**: It's a tie!

## 🛠️ Technologies Used

- **HTML5**: For the basic structure and layout.
- **CSS3**: For advanced styling, glassmorphism (`backdrop-filter`), animations, and flexbox (`style.css`).
- **JavaScript**: For the game logic, random choice generation, score tracking via `localStorage`, and DOM manipulation.

## 🚀 Getting Started

Simply clone or download this repository, ensure that `bat.png`, `ball.png`, and `stump.png` are present in the directory, and double-click on `index.html` to open it in any modern web browser. 

No installation or local server is required!

Enjoy playing!
