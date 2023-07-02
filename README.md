# Tic-Tac-Toe Game Documentation

This code is a React implementation of the Tic-Tac-Toe game. It consists of three main components: `Square`, `Board`, and `Game`.

## Square Component

The `Square` component represents a single square on the Tic-Tac-Toe board. It takes two props: `value` and `onSquareClick`. The `value` prop represents the value of the square (`X`, `O`, or `null`), while the `onSquareClick` prop is a function that is called when the square is clicked.

## Board Component

The `Board` component represents the entire Tic-Tac-Toe board. It takes three props: `xIsNext`, `squares`, and `onPlay`. The `xIsNext` prop is a boolean that indicates whether it is X's turn to play. The `squares` prop is an array of 9 elements representing the current state of the board. The `onPlay` prop is a function that is called when a play is made.

## Game Component

The `Game` component represents the entire game. It manages the game state using the `useState` hook from React. The state consists of two variables: `history` and `currentMove`. The `history` variable is an array of arrays representing the history of the game. Each element in the array is an array of 9 elements representing the state of the board at a particular point in time. The `currentMove` variable represents the current move number.

## Helper Function

The code also includes a helper function called `calculateWinner`. This function takes an array of 9 elements representing the current state of the board and returns the winner (`X`, `O`, or `null`) if there is one.
