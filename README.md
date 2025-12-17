# Dice_Challenge

## Overview  
This project is a simple *JavaScript-based dice game* built with HTML, CSS, and vanilla JavaScript. It demonstrates DOM manipulation, random number generation, and dynamic content updates. Each time the page is refreshed, two dice are rolled, and the game declares a winner between Player 1 and Player 2, or a draw if both dice show the same value.

## Features  
-  Random dice roll for both players on each refresh  
-  Automatic winner declaration (Player 1, Player 2, or Draw)  
-  Styled with custom CSS and Google Fonts for a playful design  
-  Lightweight and runs directly in the browser without dependencies  

## Tech Stack  
- *HTML5* (structure and layout)  
- *CSS3* (styling, fonts, colors)  
- *JavaScript (ES6)* (random number generation, DOM manipulation)  

## How It Works  
1. JavaScript generates two random numbers between 1 and 6.  
2. Each number corresponds to a dice image (dice1.png – dice6.png).  
3. The dice images are updated dynamically in the DOM.  
4. The game logic compares the two numbers and updates the heading (<h1>) to declare the winner or a draw.  

## Project Structure  

Dicee/
 ├── index.html      # Main HTML file
 ├── index.js        # Game logic (random dice roll + DOM updates)
 ├── styles.css      # Styling and layout
 └── images/         # Dice images (dice1.png - dice6.png)


## Installation & Usage  
```bash
# Clone the repository
git clone https://github.com/your-username/dicee-game.git

# Navigate to project folder
cd dicee-game

# Open index.html in your browser
