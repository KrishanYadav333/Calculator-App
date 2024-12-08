# Calculator App

A simple graphical calculator application built using Python's **Tkinter** library. This app supports basic arithmetic operations, including addition, subtraction, multiplication, division, exponentiation, and more.

---

## Features
- **Basic Operations**: Addition, Subtraction, Multiplication, Division.
- **Advanced Operations**: Exponentiation (`^`).
- **User-Friendly Interface**: Buttons for input, clear, backspace, and evaluation.
- **Error Handling**: Displays an alert if attempting division by zero.
- **Responsive Design**: Buttons adjust dynamically for a seamless experience.

---

## Installation and Usage
1. **Requirements**:  
   Ensure you have Python 3 installed. Tkinter comes pre-installed with most Python distributions.
   
2. **Clone the Repository**:
   ```bash
   git clone <https://github.com/KrishanYadav333/Calculator-App/tree/main>
   cd <Calculator App Using Python>
   ```

3. **Run the Calculator**:
   Run the script directly using Python:
   ```bash
   python calculator.py
   ```

4. **Use the Calculator**:
   - Launch the app, and click buttons or use the keyboard to input expressions.
   - Press `=` to calculate the result.
   - Use `C` to clear the input and `<-` to delete the last character.

---

## Code Structure
- **`get_input`**: Appends the clicked button value to the entry widget.
- **`backspace`**: Removes the last character from the entry field.
- **`clear`**: Clears all input.
- **`calc`**: Evaluates the mathematical expression in the entry field.
- **`popupmsg`**: Displays a popup alert for invalid operations (e.g., division by zero).
- **`cal`**: Initializes the Tkinter app and creates the interface.

---

## Screen Layout
- Numeric buttons are arranged in a 4x4 grid.
- Special buttons (`+`, `-`, `*`, `/`, `^`, `C`, `<-`, `=`) are color-coded for easy identification.
- A single entry field displays the user input and results.

