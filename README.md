
---

# Interactive Basic Calculator

This is a simple interactive basic calculator implemented in Python. It performs addition, subtraction, multiplication, and division operations, and includes error handling for various scenarios.

## Features

- Addition
- Subtraction
- Multiplication
- Division (with error handling for division by zero)
- User-friendly input and error messages
- Option to perform multiple calculations in a session

## How to Use

1. Clone the repository or download the Python script (`calculator.py`).
2. Run the script in your preferred Python environment.

```bash
python calculator.py
```

3. Follow the on-screen instructions to input numbers and select an operator.
4. View the result of the calculation.
5. Optionally, choose to perform another calculation.

## Error Handling

- Invalid input: Displays an error message if the user enters an invalid number or operator.
- Division by zero: Raises a `ValueError` if the user attempts to divide by zero.
- Unexpected errors: Catches unexpected errors and displays an error message.

## Example

```plaintext
Enter the first number: 10
Enter an operator (+, -, *, /): *
Enter the second number: 5
Result: 50.0
Do you want to perform another calculation? (yes/no): yes
Enter the first number: 12
Enter an operator (+, -, *, /): /
Enter the second number: 0
Error: Cannot divide by zero
Do you want to perform another calculation? (yes/no): no
```

---
