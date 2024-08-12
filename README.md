# Chess Game

This is a web-based Chess game built using [Chess.js](https://github.com/jhlywa/chess.js) for the game logic and [Express.js](https://expressjs.com/) for the server-side functionality.

## Features

- **Play against AI or a friend**: The game allows you to play against a basic AI or another player.
- **Legal Moves**: Chess.js ensures all moves follow the rules of chess.
- **Move Validation**: Prevents illegal moves with detailed error handling.
- **Simple UI**: A clean and minimalistic user interface.
- **Real-Time Game Updates**: Moves are updated in real-time on both sides.
- **Undo Functionality**: Allows you to undo the last move.

## Technologies Used

- **Frontend**:
  - HTML5
  - CSS3
  - JavaScript (Vanilla)
  
- **Backend**:
  - Node.js
  - Express.js
  
- **Game Logic**:
  - Chess.js

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/chess-game.git
   cd chess-game
2. **Install dependencies**:
   ```bash
   npm install
3. **Start the server**:
   ```bash
   nodemon app.js
4. Open your browser and go to http://localhost:3000 to start playing.

## How to Play
1. Load the game in your web browser.
2. Choose a mode: Play against AI or another player.
3. Make your move: Click on a piece to select it, and then click on a valid square to move it.
4. Check the status: The game will notify you if you are in check, checkmate, or stalemate.
5. Undo a move: Use the "Undo" button to reverse the last move.

## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request if you have any ideas to improve the game.

## Acknowledgments
Chess.js for the excellent chess logic.
Express.js for providing a robust server framework.
