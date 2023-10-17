# PY-app
This Python program is designed to classify an input number into one of three categories: even, negative, or odd. Here's a description of the program and how to use it:

# Description:

1. The program starts by prompting the user to enter an integer, which is assigned to the variable 'a' using the input function and then converted to an integer using int(). <br>
2. It uses an if statement to perform three checks on 'a' in the following order:
*   If 'a' is divisible by 2 (i.e., it has no remainder when divided by 2), it prints "Juft son," indicating that 'a' is an even number.
*   If 'a' is less than 0 (negative), it prints "Siz manfiy son kiritdingiz," indicating that 'a' is a negative number.
*   If 'a' doesn't meet either of the above conditions, it prints "Toq son," indicating that 'a' is an odd number.
3. The program displays the result to the user. <br>

# How to Use:

1. Run the program typing with the method
```
python test.py
```
2. Enter an integer when prompted.
3. The program will analyze the input number and display one of the following messages:
*   If the number is even (e.g., 4), it will display "Juft son."
*   If the number is negative (e.g., -3), it will display "Siz manfiy son kiritdingiz."
*   If the number is odd (e.g., 7), it will display "Toq son."
4. The program categorizes the input number based on whether it's even, negative, or neither, and provides feedback to the user accordingly.