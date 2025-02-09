# Tic-Tac-Toe
Creating a tic-tac-toe game in react

## The app is structured into three main components:

### Game (Parent Component)
- Manages the game state (history and currentMove).
- Renders the Board component and a list of past moves.
### Board (Child of Game)
- Receives the current game state from Game as props.
- Handles the logic for player moves and determines the game status.
- Renders the 3x3 grid of Square components.
### Square (Child of Board)
- Represents a single cell in the Tic-Tac-Toe grid.
- Calls the onSquareClick function when clicked, updating the game state.

My project uses React’s useState to manage the history of moves and the current state of the board. Props are used to pass the board state (squares) and click handlers (onPlay, onSquareClick) from parent components (Game and Board) down to Square, allowing dynamic updates.

## This Tic-Tac-Toe app showcases React component structure, props, and state management:

- Components: The app is divided into Game, Board, and Square components for modularity.
- Props: Used to pass game state and event handlers between components.
- useState: Manages game history, move tracking, and UI updates dynamically.
