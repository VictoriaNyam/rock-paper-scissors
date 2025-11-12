# rock-paper-scissors
# 🪨 Rock Paper Scissors Game

A simple and fun **Rock–Paper–Scissors** web game built using **HTML**, **CSS**, and **JavaScript**.  
Play against the computer, track your wins, losses, and ties — all stored in your browser’s local storage!

---

##  Features

- Randomized computer moves  
- Persistent score tracking using `localStorage`  
- Reset button to clear scores  
- Responsive and minimalistic design  
- Visual emojis for each move (Rock, Paper, Scissors)

##  Project Structure
rock-paper-scissors/
│
├── 10-rock-paper-sc.html # Main HTML file
├── 10-rock-paper-sc.css # Stylesheet for layout and design
├── 10-rock-paper-sc.js # Core game logic and DOM manipulation
└── asset/ # Folder for emoji images
├── rock-emoji.png
├── paper-emoji.png
└── scissors-emoji.png


## How It Works

1. Click one of the move buttons (Rock, Paper, or Scissors).
2. The computer randomly selects a move.
3. The game determines the result:
   - Rock beats Scissors  
   - Scissors beats Paper  
   - Paper beats Rock  
4. The result and updated scores appear on the screen.
5. Scores are automatically saved in `localStorage`, so your progress stays even after refreshing.

##  Setup & Usage

1. Clone or download this repository.
2. Make sure the `asset/` folder contains:
   - `rock-emoji.png`
   - `paper-emoji.png`
   - `scissors-emoji.png`
3. Open the `10-rock-paper-sc.html` file in any modern web browser.
4. Play the game!
   

---
