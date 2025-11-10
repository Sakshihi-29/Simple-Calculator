# Simple Calculator 🧮

This is a basic Python program that performs simple arithmetic operations — addition, subtraction, multiplication, and division — between two numbers.

## 📄 Description

The program takes user input for an arithmetic operation (`+`, `-`, `*`, `/`) and performs the corresponding calculation on two predefined numbers (`a = 12`, `b = 4`).

### Example

```python
a = 12
b = 4
choice = input("Enter your choice +, -, *, /: ")

if choice == "+":
    print(a + b)
elif choice == "-":
    print(a - b)
elif choice == "*":
    print(a * b)
elif choice == "/":
    print(a / b)
else:
    print("Invalid choice")
