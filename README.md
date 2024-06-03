# Tic Tac Toe Game

This repository contains the code for a simple [Tic Tac Toe](https://tic-tac-toe-ga.netlify.app/) game implemented in HTML, CSS, and JavaScript. The game allows two players to play Tic Tac Toe in a web browser, with functionality to start a new game and reset the current game. 

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Game Logic](#game-logic)
- [Styling](#styling)
- [Contributing](#contributing)
- [License](#license)

## Demo

You can try out the game [here](#).

## Features

- Two-player gameplay (Player O and Player X)
- Reset the current game
- Start a new game
- Display a message indicating the winner
- Simple and intuitive UI

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)

## Getting Started

To get a local copy of the project up and running, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/tic-tac-toe.git
    ```

2. Navigate to the project directory:
    ```bash
    cd tic-tac-toe
    ```

3. Open `index.html` in your preferred web browser:
    ```bash
    open index.html
    ```

## Game Logic

The game logic is implemented in `app.js`. Here's a breakdown of the key functions:

- **winPatterns**: An array containing all possible winning combinations.
- **resetGame**: Resets the game state and hides the winner message.
- **disableBoxes**: Disables all the boxes once a player wins.
- **enableBoxes**: Enables all the boxes and clears their content for a new game.
- **showWinner**: Displays the winner message and disables further moves.
- **checkWinner**: Checks for a winning combination after each move.

## Styling

The game's styling is defined in `style.css`. Key elements include:

- **body**: Sets the background color and text alignment.
- **.container**: Centers the game board.
- **.game**: Defines the layout of the game board.
- **.box**: Styles each box in the Tic Tac Toe grid.
- **#reset-btn** and **#new-btn**: Styles the reset and new game buttons.
- **#msg**: Styles the winner message.
- **.msgcontainer**: Centers the winner message on the screen.
- **.hide**: Hides elements that should not be visible.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to create an issue or submit a pull request.

1. Fork the repository.
2. Create your feature branch:
    ```bash
    git checkout -b feature/YourFeature
    ```
3. Commit your changes:
    ```bash
    git commit -m 'Add some feature'
    ```
4. Push to the branch:
    ```bash
    git push origin feature/YourFeature
    ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

**Contact Us:**
If you have any questions or inquiries, you can reach out to us via email at [umarabdullah.work@gmail.com](mailto:umarabdullah.work@gmail.com).

Enjoy playing Tic Tac Toe! If you have any questions or feedback, feel free to reach out.