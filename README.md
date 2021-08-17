# Tic-React-Toe

A simple game of Tic-Tac-Toe made in react to show parent-child interaction

## Roadmap of Future Improvements

- Implement finishing state for the game
- Don't allow continuing clicking of the squares if a `<Square/>` has been set already by a given player
- Replay button to restart a game, or when a finishing state is already set, to be able to replay a new game
- Implement simple AI
  Could be used with a Minimax algorithm, which gives weights to a tree of probable plays,
  or brute force the matrix of positions on each play
- Keep a high score of players, based on won matches
  Would implement entering the names of the players, and store their wins and keep tabs on them
