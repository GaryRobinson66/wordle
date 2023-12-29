# Wordle Game Project

Welcome to the Wordle Game project! This web-based game was created to challenge users' word-guessing abilities while providing an engaging and interactive experience. The project is primarily built using HTML, CSS, and JavaScript.

## url

https://www.youtube.com/watch?v=rTC1sRRyoSY

## Project Description

### For my CS50 final project, I aimed to learn more about JavaScript as I felt it was an area where I had little knowledge. I decided that creating a game would be a great way to delve deeper into JavaScript. I chose Wordle as the game, as it requires a moderate level of coding complexity that I could learn from without being discouraged.

### In the game, the user is given multiple attempts to guess a five-letter word. As the user attempts to solve the puzzle by submitting possible answers, hints will be provided with letters colored in yellow or green if the letters are guessed correctly. When the user correctly answers all five letters and completes the puzzle, the answer will turn green, and the user will be presented with a refresh button to start a new game. If the user enters an invalid word, the game will display an error message and prompt the user to start a new game.

## Project Structure

The project consists of the following key files:

### 1. `index.html`

The main HTML file (`index.html`) serves as the entry point for the game. It defines the structure of the game board, including the header, main board, refresh button, and footer. The file also links to external CSS styles (`styles.css`) and JavaScript logic (`script.js`).

### 2. `styles.css`

The CSS file (`styles.css`) contains styling rules for various elements within the game. It defines the appearance of the game board, tiles, keyboard, and other UI components. The use of flexbox and grid layouts ensures a responsive and visually appealing design.

### 3. `script.js`

### **Initialization and Setup**

The JavaScript file (`script.js`) begins by initializing variables such as the board dimensions (`height` and `width`), current row and column (`row` and `col`), and the game state (`gameOver`). The `word` variable holds the target word that the player needs to guess, initially set to "FRAME." Additionally, the `guessList` array contains possible valid words for the game. The `window.onload` event triggers the `initialize()` function once the page is fully loaded.

### **Board Initialization**

The `initialize()` function sets up the game board on the HTML page. It creates a grid of tiles where the player can input their guesses.

### **Keyboard Input Processing**

The `processKey()` function is called when a key on the on-screen keyboard is clicked. It handles the logic for processing the input, including adding letters to the board and handling special keys like "Enter" and "Backspace."

### **Main Game Logic**

The `update()` function is crucial for updating the game state after each guess. It checks the validity of the word, identifies correct and incorrect letters, and updates the visual representation of the board.

### **Showing the Refresh Button**

The `showRefreshButton()` function is called when the game is over. It displays the "New Game!" button, allowing the player to reset the game.

These are the key functions and logic snippets in the `script.js` file. The code is structured to be readable and modular, making it easy to understand and modify. The script handles user input, updates the game state, and provides feedback to create an interactive gaming experience. Feel free to explore and experiment with the code to deepen your understanding of JavaScript in the context of a real-world project.

## Design Choices

### 1. Responsive Design

The project incorporates a responsive design approach to ensure an optimal gaming experience on various screen sizes. Flexbox and grid layouts were chosen for their simplicity and effectiveness in arranging UI elements.

### 2. Game Logic

The game logic is implemented to facilitate a smooth and interactive user experience. Users can input letters via an on-screen keyboard, and the game provides real-time feedback on correct and incorrect guesses. The design allows for easy customization of the game parameters such as board dimensions and word lists.

### 3. Learning Focus

The primary goal of this project was to learn JavaScript. As a result, certain design choices, such as the structure of the code and the use of event listeners, were made to reinforce fundamental JavaScript concepts. The project serves as a practical application of JavaScript skills gained during the learning process.

## Getting Started

To start playing the Wordle game, simply open the `index.html` file in a web browser. The game will load, and you can begin guessing the hidden word. If needed, the game can be reset using the "New Game!" button.

