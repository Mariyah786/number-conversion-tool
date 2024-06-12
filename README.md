# number-conversion-tool

Objective:
The aim of this project is to create an interactive command-line tool in Python that allows users to convert numbers between various numeral systems and measurement units. The project provides a practical way to understand and apply different conversion algorithms, enhancing both programming and mathematical skills.

Features:
1. Decimal to Hexadecimal Conversion:
   Converts a decimal (base-10) number to its equivalent hexadecimal (base-16) representation. The result is prefixed with `0x`.

2. Hexadecimal to Decimal Conversion:
   Converts a hexadecimal (base-16) number (prefixed with `0x`) to its equivalent decimal (base-10) representation.

3. Decimal to Octal Conversion:
   Converts a decimal (base-10) number to its equivalent octal (base-8) representation. The result is prefixed with `0`.

4. Octal to Decimal Conversion:
   Converts an octal (base-8) number (prefixed with `0`) to its equivalent decimal (base-10) representation.

5. Decimal to Binary Conversion:
   Converts a decimal (base-10) number to its equivalent binary (base-2) representation.

6. Binary to Decimal Conversion:
   Converts a binary (base-2) number to its equivalent decimal (base-10) representation.

7. Octal to Binary Conversion:
   Converts an octal (base-8) number to its equivalent binary (base-2) representation.

8. Gallons to Liters Conversion:
   Converts a volume measurement from gallons to liters.

9. Liters to Gallons Conversion:
   Converts a volume measurement from liters to gallons.

Instructions for Use:
1. Upon running the program, the user is presented with a menu of conversion options.
2. The user selects an option by entering the corresponding number or chooses 'x' to exit the program.
3. The program then prompts the user to input the number they wish to convert.
4. The input is validated to ensure it falls within the specified range (0 to 2048 for decimal numbers) or is a valid numeric input.
5. The program performs the conversion and displays the result.
6. The process repeats until the user chooses to exit.

Implementation Details:
- The project employs fundamental programming constructs such as loops, conditionals, and exception handling.
- Each conversion function includes input validation to handle errors and ensure the correctness of the user's input.
- String manipulation and mathematical operations are used to perform the conversions.
- The code is structured to be user-friendly and provides clear error messages for invalid inputs.

Assumptions:
- The allowable range for decimal input is 0 to 2048; if the user enters a number outside this range, an error message is displayed.
- Users can exit the program only by selecting 'x'.
- Hexadecimal input must start with '0x'.
- Octal input must start with '0'.
- Binary input must consist of 0s and 1s only.
- The program does not accept any non-numeric string values as valid input.

