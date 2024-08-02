# Tic-Tac-Toe Game

This project is a simple implementation of the classic Tic-Tac-Toe game, built using React. The game allows two players to take turns marking a 3x3 grid with "X" and "O". The first player to align three marks horizontally, vertically, or diagonally wins the game.

## Project Structure

The project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

The main files and directories are:
- `public/`: Contains the public assets of the project.
- `src/`: Contains the source code of the application.
  - `index.js`: The entry point for the React application.
  - `App.js`: The main component of the application.
  - `components/`: Directory for reusable React components (e.g., Board, Square).
  - `App.css`: The main stylesheet for the application.
  - `index.css`: Basic styles for the React application.
- `README.md`: Project documentation.

## Getting Started

### Prerequisites

Before you begin, ensure you have Node.js and npm installed on your system. You can download them from [nodejs.org](https://nodejs.org/).

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/tic-tac-toe.git

2. Navigate to the project directory:
    cd tic-tac-toe

3. Install the dependencies:
    npm install

4. Start the development server:
    npm start

The application will automatically open in your default web browser. If it doesn't, visit http://localhost:3000 to view it.

## Features
- Interactive Gameplay: Two players can take turns by clicking on the grid squares to  make their move.
- Winner Detection: The game detects when a player has won by aligning three marks in a row, column, or diagonal.
- Responsive Design: The application is responsive and works on both desktop and mobile devices.

## How to Play
1) The game starts with an empty 3x3 grid.
2) Players take turns to click on an empty square to place their mark ("X" or "O").
3) The first player to get three marks in a horizontal, vertical, or diagonal line wins the game.
4) If all nine squares are filled and no player has three in a row, the game is declared a draw.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contributing
If you want to contribute to this project, feel free to fork the repository, create a new branch, and submit a pull request with your changes. Contributions are welcome!

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
