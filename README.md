# WebProject
Calculator
-----------
calculator/
├── calc.html        # Main HTML structure of the calculator
├── index.css        # Styling for the calculator UI
├── index.js         # JavaScript logic for calculator functionality

🚀 Features

Simple and intuitive design
Supports basic arithmetic operations (+, −, ×, ÷)
Real-time calculation display
“Clear” button to reset the screen
Lightweight and responsive UI

🧩 How It Works

1. calc.html
Contains the structure of the calculator using an HTML <table>.
Each button triggers JavaScript functions like display(), calculate(), or clearScreen() through onclick events.

2. index.css
Handles the styling — adds colors, shadows, and rounded buttons for a modern look.

3. index.js
Implements the main logic:

display(value) → Displays pressed keys on the screen.
clearScreen() → Clears the calculator display.
calculate() → Evaluates the expression using eval() and displays the result.

🖥️ How to Run

1. Download all files (calc.html, index.css, index.js) into the same folder.
2. Open calc.html in any web browser.
3. Start performing calculations!

Example:
Input: 7 + 3 * 2
Output: 13

📸 UI Preview

A calculator interface with:
* Light blue background
* Green “C” (Clear) and “=” buttons
* Rounded white numeric and operator buttons

 ⚠️ Note

1. The project uses JavaScript’s eval() function for expression evaluation.
Avoid entering non-mathematical inputs as it can cause runtime errors.

2. For enhanced security, you can replace eval() with a safer math parser in future improvements.

🧠 Future Enhancements

1. Add keyboard input support
2. Include advanced operations (square root, power, percentage)
3. Display calculation history
4. Add a dark/light theme toggle

 👨‍💻 Author
Suhas Singh
Simple calculator project built to demonstrate DOM manipulation and basic JavaScript event handling.

   
