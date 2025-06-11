```markdown
# Calculator Project

A web-based calculator with a sleek, transparent design. It performs addition, subtraction, multiplication, division, and supports parentheses and keyboard input.

## What's Used
- Python/Flask: Runs the web server.
- HTML: Builds the calculator layout.
- CSS: Creates a glassmorphism style with blurred background and colorful buttons.
- JavaScript: Powers calculator functions and keyboard controls.

## Installations Needed
- Python 3.6+: Get it from https://www.python.org/downloads/
- Flask: Install with `pip install flask`
- A web browser (Chrome, Firefox, etc.).

## Setup Instructions
1. Get the Project:
   - Clone it: `git clone https://github.com/username/calculator_project.git`
   - Or create a `calculator_project` folder with these files:
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
2. Install Flask:
   - Run: `pip install flask`
3. Start the Server:
   - Go to the project folder: `cd calculator_project`
   - Run: `python app.py`
4. Open the Calculator:
   - Visit `http://127.0.0.1:5000/` in your browser.

## How to Use
- With Mouse:
  - Click numbers (0-9) or decimal point (.).
  - Click operators (+, -, ×, ÷) or parentheses ((), )).
  - Click `C` to clear, `←` to delete last, `=` to calculate.
- With Keyboard:
  - Type numbers (0-9), `.` for decimal.
  - Use `+`, `-`, `*` (for ×), `/` (for ÷), `(` or `)`.
  - Press `Enter` to calculate, `Escape` to clear, `Backspace` to delete.
```