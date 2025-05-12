# Tic Tac Toe AI

## Description
Tic Tac Toe AI is an interactive web application built with Next.js and React, allowing users to play Tic Tac Toe against an AI opponent. The AI employs a strategic algorithm to make defensive and offensive moves, ensuring a challenging gameplay experience. The application features a responsive design with a visually appealing interface, including gradient backgrounds and hover effects.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements)

## Installation
To run the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/tic-tac-toe-ai.git
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
│   │   ├── ticTacToe/
│   │   │   ├── ttt.module.css   # Styles for the Tic Tac Toe component
├── package.json                 # Project dependencies and scripts
├── README.md                    # Project documentation
```

## Contributing
Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit them (`git commit -m 'Add your feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.

Please ensure your code follows the project's coding standards and includes appropriate tests.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
- **Author**: Rishik Tech
- **Email**: rishiktech@example.com
- **GitHub**: [your-username](https://github.com/your-username)

## Acknowledgements
- Inspired by classic Tic Tac Toe games.
- Thanks to the Next.js and React communities for their excellent documentation and resources.