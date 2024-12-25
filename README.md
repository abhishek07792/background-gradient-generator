# background-gradient-generator
# Random Gradient Background Generator

This project allows users to dynamically generate a gradient background using two clickable buttons that each generate random colors. When a user clicks on either of the buttons, the background of the page updates with a linear gradient between the two new random colors. The CSS code for the gradient is displayed in a designated section of the page, and users can easily copy it to their clipboard with a click.

## Features

- **Random Color Generation**: Each button generates a random color on click, which updates the button’s background color and the page’s gradient background.
- **CSS Copying**: The generated gradient’s CSS (`background-image`) is displayed and can be copied to the clipboard with a simple click.
- **Responsive**: The design adjusts well to different screen sizes.

## How it Works

1. **Buttons**: There are two buttons (`#btn1` and `#btn2`). Clicking on them generates random colors for each button. These colors are then applied to the background gradient of the page.
   
2. **CSS Display**: The `background-image` CSS property for the gradient is displayed in a `.copy` div element. Users can click this div to copy the CSS code.

3. **Gradient Update**: The background gradient on the page is updated every time a button is clicked, resulting in a visually dynamic page.

## Technologies Used

- **HTML**: For the structure of the page.
- **CSS**: Used for basic styling (the `style.css` file is linked, but its contents are not included in this repo).
- **JavaScript**: Used for random color generation, event handling, and copying the CSS to the clipboard.


## Installation

To run this project locally:

1. Clone this repository:
   ```bash
   git clone https://github.com/abhishek07792/background-gradient-generator.git
2. Open index.html in your browser to view the project.
   How to Use
   Click on the Buttons: Click either #btn1 or #btn2 to generate new random colors for the buttons and the page’s background.
   Copy the CSS: Click on the background-image text shown on the page to copy the CSS code for the gradient to your clipboard.
License
This project is licensed under the MIT License - see the LICENSE file for details.
