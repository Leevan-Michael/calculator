```markdown
# Calculator Project

A web-based calculator with a modern, transparent design. It performs basic math operations like addition, subtraction, multiplication, and division, and supports parentheses and keyboard input.

## What Is Used
- **Python/Flask**: Backend to serve the web application.
- **HTML**: Structures the calculator interface.
- **CSS**: Styles the calculator with a glassmorphism look (blurred background, vibrant buttons).
- **JavaScript**: Handles calculator logic, input, and keyboard events.

## Installations Needed
- **Python 3.6 or higher**: Download from https://www.python.org/downloads/
- **Flask**: Python library for the web server.
  - Install with: `pip install flask`
- A web browser (e.g., Chrome, Firefox).

## Setup Instructions
1. **Clone or Create the Project**:
   - Clone the repository: `git clone https://github.com/username/calculator_project.git`
   - Alternatively, create a folder named `calculator_project` and set up the files as shown:
     ```
     calculator_project/
     ├── app.py
     ├── static/
     │   ├── css/
     │   │   └── styles.css
     │   └── js/
     │       └── script.js
     ├── templates/
     │   └── index.html
     └── README.md
     ```
2. **Install Dependencies**:
   - Open a terminal and run: `pip install flask`
3. **Run the Project**:
   - Navigate to the project folder: `cd calculator_project`
   - Start the server: `python app.py`
4. **Open the Calculator**:
   - In a browser, go to `http://127.0.0.1:5000/`

## How to Use
- **Using the Mouse**:
  - Click number buttons (0-9) to enter numbers.
  - Click operators (+, -, ×, ÷) for calculations.
  - Click `(` or `)` for parentheses.
  - Click `C` to clear, `←` to delete the last character, `=` to get the result.
- **Using the Keyboard**:
  - Press number keys (0-9), `.` for decimal, `+`, `-`, `*` (for ×), `/` (for ÷).
  - Press `(` or `)` for parentheses.
  - Press `Enter` to calculate, `Escape` to clear, `Backspace` to delete.
```