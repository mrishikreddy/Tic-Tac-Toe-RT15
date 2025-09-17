# Tic Tac Toe AI

Tic Tac Toe AI is an interactive web application built with Next.js and React, allowing users to play Tic Tac Toe against an AI opponent. The AI employs a strategic algorithm to make defensive and offensive moves, ensuring a challenging gameplay experience. The application features a responsive design with a visually appealing interface, including gradient backgrounds and hover effects.

[Visit Live Project](https://mrishikreddy.github.io/rishik.tech.projects/ticTacToe)

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Acknowledgements](#acknowledgements)

## Installation
To run the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/mrishikreddy/Tic-Tac-Toe-RT15.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd tic-tac-toe-ai
   ```

3. **Install dependencies**:
   ```bash
   npm install
   ```

4. **Start the development server**:
   ```bash
   npm run dev
   ```

5. Open your browser and visit `http://localhost:3000`.

## Usage
- **Start the Game**: Open the application in your browser.
- **Play as X**: Click on any cell in the 3x3 grid to place your "X".
- **AI Opponent**: The AI (playing as "O") will respond automatically after a short delay.
- **Game Outcome**: The game ends when there is a winner or a draw, displaying the result.
- **Play Again**: Click the "Play Again" button to reset the board and start a new game.

## Features
- **Interactive Gameplay**: Play Tic Tac Toe against a smart AI.
- **Responsive Design**: Adapts to various screen sizes, including mobile devices.
- **Strategic AI**: Uses a rule-based algorithm to prioritize winning and blocking moves.
- **Visual Feedback**: Displays whose turn it is and the game result.
- **Stylish UI**: Gradient backgrounds, hover effects, and shadows for an enhanced user experience.

## Technologies Used
- **Next.js**: React framework for server-side rendering and static site generation.
- **React**: For building the user interface.
- **CSS Modules**: For scoped and modular styling.
- **JavaScript (ES6+)**: For game logic and AI implementation.

## Project Structure
```plaintext
tic-tac-toe-ai/
├── src/
│   ├── app/
│   │   ├── page.js              # Main Tic Tac Toe component
│   │   ├── ttt.module.css       # Styles for the Tic Tac Toe component
│   │   │   
├── package.json                 # Project dependencies and scripts
├── README.md                    # Project documentation
```

## Acknowledgements
- Inspired by classic Tic Tac Toe games.
- Thanks to the Next.js and React communities for their excellent documentation and resources.
