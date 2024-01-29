# Project Name

Tic-Tac-Toe Website with React

### Motivation

I embarked on this project to delve into React, a versatile framework ideal for various applications and websites. Following the tutorial on the React website ([Tutorial Link](https://react.dev/learn/tutorial-tic-tac-toe)), I sought to master the fundamentals of React development.

### Project Overview

The project materialized as a Tic-Tac-Toe game that not only lets players engage in the classic game but also revisit the game's history. Leveraging the create-react-app module streamlined the development process.

![Alt text](./Tic-Tac-Toe%20Example.png)

### Features

1. **Rendering a Board of Squares**

   - A 3x3 grid of squares was rendered, with each square defined as a component. These components were then employed to construct the game board in the Game class.

2. **Updating the Square when Clicked**

   - Ensured that when a square is clicked, it updates with either "X" or "O" depending on the turn.

3. **Updates Current Turn when Square is Updated**

   - Implemented functionality to update the current player with each turn.

4. **Calculating Winner**

   - Incorporated a winner calculation feature based on matching elements in a line. The game concludes when a winner is detected.

5. **History**
   - Enabled players to navigate the game's history, facilitating a review or the option to replay moves.

### Learnings

The project was an invaluable learning experience, providing insights into the effective use of React's props, components, and the overall framework.

### Future Improvements

While the core functionality is robust, the website's aesthetics could be enhanced for a more engaging user experience.

### How to Use

**Prerequisites:**

- Node.js

Run in Terminal of File any of:
**Commands:**

- `npm start`: Launches the app in development mode at http://localhost:3000, with automatic page reloading.
- `npm test`: Initiates the test runner in interactive watch mode.
- `npm run build`: Builds the app for production, optimizing and bundling React.
- `npm run eject`: A one-way operation offering full control over configurations for advanced customization.

Remember, ejecting is optional, and the default features suffice for small to medium deployments.

### Acknowledgements

This project was crafted with guidance from the excellent tutorial provided by the React dev team ([Tutorial Link](https://react.dev/learn/tutorial-tic-tac-toe)).

### License

This project is licensed under the Apache License 2.0 - see the [LICENSE.md](LICENSE.md) file for details.
