# 🔢 #100Devs Push Project001: Calculator

## Description
A simple calculator built with HTML, CSS, and JS.

Features
- Clickable buttons for numbers and operators
- Prevents multiple decimals in a number
- Allows negative numbers (must enter `-` as the first input)
- Prevents inputting multiple operators in a row (last entered operator overwrites others)
- Evaluates expressions with correct order of operations
- Dynamic font resizing to fit results on the display
- Clear button to reset everything

How It Works
- Numbers and operators are stored in an array as you click.
- Pressing `=` evaluates the array
- The result is displayed on screen, font size adjusts automatically if needed to fit in the results window

Project Structure
- `index.html`: main HTML file
- `style.css`: calculator styling
- `script.js`: calculator functions and interaction handling

Usage
1. Clone or download this repository
2. Open `index.html` in your browser
3. Start clicking buttons to calculate something!

Limitations and areas for future improvements:
- Handling of undefined results only gives "Infinity" as an answer currently
- Keyboard input is not supported
- No parentheses or advanced operations available
- Object-based operator methods will be added
