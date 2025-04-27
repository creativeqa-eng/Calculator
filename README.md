# Calculator
This calculator computes addition, subtraction, division and multiplication.

# Simple Calculator

A basic Java console application that performs addition, subtraction, multiplication, and division based on user input.

## 📋 Features

- Accepts two numbers from the user.
- Allows the user to choose an operation:
  - Addition
  - Subtraction
  - Multiplication
  - Division
- Handles division by zero gracefully.
- Displays the result of the operation.

## 🛠️ How It Works

1. The user is prompted to enter two numbers.
2. The user selects the desired operation.
3. The program performs the selected operation and displays the result.
4. If the user attempts to divide by zero, an error message is displayed.

## 💻 Usage

1. Compile the program:

```bash
javac Calculator.java
```

2. Run the program:

```bash
java Calculator
```

3. Follow the prompts:
   - Enter the first number
   - Enter the second number
   - Choose an operation (1-4)

## 📦 Example

```
Enter the first number
10
Enter the second number
5
Choose an operation
1. Addition
2. Subtraction
3. Multiplication
4. Division
3
Result: 50.0
```

## 📄 Code Structure

- **Input Collection**: Gathers two numbers and an operation choice from the user.
- **Operation Handling**:
  - **Addition**: Adds the two numbers.
  - **Subtraction**: Subtracts the second number from the first.
  - **Multiplication**: Multiplies the two numbers.
  - **Division**: Divides the first number by the second (with zero division check).
- **Output**: Prints the result or an error message.

## 🧹 Requirements

- Java JDK 8 or later

## 📚 Future Improvements

- Support more operations like modulus and exponentiation.
- Add continuous calculations (like a calculator history).
- Implement input validation to handle invalid entries.
- Create a graphical user interface (GUI) version.
