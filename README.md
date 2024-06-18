# Responsive Chessboard
This repository contains two HTML files that create and display a chessboard using different layout techniques: grid and flexbox. Both projects feature a complete chessboard with pieces positioned at their initial positions. Additionally, Sass is used for more efficient and manageable styling.

## Project Structure
- **index.html (grid)**: Chessboard using CSS Grid layout
- **index.html (flex)**: Chessboard using CSS Flexbox layout
- **style.css**: Compiled CSS stylesheet for both HTML files
- **style.scss**: Sass source file for styling
- **script.js**: JavaScript file for interactivity (if needed)
- **chess-pieces/**: Directory containing images of the chess pieces
  
## File Descriptions
### index.html (grid)
This file creates a chessboard using a CSS Grid layout. The structure includes:

- A button element for starting or interacting with the game.
```<input type="button" id="button" value="Play">```
- The container for the chessboard.
```<div class="board">```
- Each square of the board is represented by either a box1 or box2 class.
- Chess pieces are placed within div elements with the class piece.
  
### index.html (flex) 
This file creates a chessboard using a CSS Flexbox layout. The structure includes:

- A button element for starting or interacting with the game.
```<input type="button" id="button" value="Play">```
- The container for the chessboard border.
```<div class="border">```
- The container for the chessboard itself.
```<div class="board">```
- Each square of the board alternates between light and green classes to represent the colors of the squares.
- Chess pieces are placed within div elements with the class piece.
  
### style.scss
This file contains the Sass source code for styling the chessboard. Key features include:

- Variables for colors and dimensions to maintain consistency.
- Nested rules for better organization of styles.
- Grid and flexbox layout properties for the chessboard.
- Styling for the chessboard squares (box1, box2, light, green).
- Styling for the chess pieces (piece).
  
### style.css
This file is the compiled CSS output from the style.scss file. It contains all the styles needed for the chessboard, ready to be linked in the HTML files.

### script.js
This file is intended for any JavaScript needed to add interactivity to the chessboard. It is currently linked but does not contain any scripts.

### chess-pieces/
This directory contains images of all the chess pieces in both black and white colors. The images are used to represent the pieces on the board.

## Usage
To view the chessboards:

- Clone or download the repository to your local machine.
- Ensure all files (index.html, style.css, script.js, style.scss, and the chess-pieces directory) are in the same directory.
- If you make changes to style.scss, compile it to style.css using a Sass compiler.
- Open either index.html from flexbox or grid directory in a web browser to view the chessboard created using the respective layout method.

## Credits
The images of the chess pieces are sourced from various free resources. This project is for educational purposes to demonstrate different layout techniques in web development.

## License
This project is for personal and educational purposes only. All content related to chess pieces and chessboard layouts are used for demonstration and educational purposes.
