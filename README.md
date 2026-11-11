# Java Scanner Example – Sum of Two Numbers

A small Java console program that reads two integers from the user with `Scanner` and prints their sum.

## What It Demonstrates

- Importing and creating a `Scanner` to read keyboard input
- Reading integers with `nextInt()`
- Declaring several variables on one line (`int a, b, s;`)
- Adding the numbers and printing the result

## How It Works

1. The program asks for `a` and reads an integer.
2. It asks for `b` and reads another integer.
3. It calculates `s = a + b` and prints the result.

## Sample Run

```
Enter a:
12
Enter b:
30
Sum = 42
```

## Requirements

- Java Development Kit (JDK) 8 or higher

## Getting Started

```bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>
javac ScannerX.java
java ScannerX
```

## Notes

- Entering something that is not a whole number, such as `3.5` or `abc`, throws an `InputMismatchException` and stops the program.
- The `Scanner` is never closed. This is harmless in a small program like this, but `obj.close()` is good practice.
- Because the variables are `int`, very large numbers can overflow.

## Project Structure

```
.
├── ScannerX.java
└── README.md
```

## Possible Improvements

- Handle invalid input with `hasNextInt()` or `try-catch`
- Use `double` to accept decimal numbers
- Add subtraction, multiplication, and division
- Close the `Scanner` at the end
