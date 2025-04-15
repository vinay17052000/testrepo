# COBOL Even Numbers Program

This project contains a COBOL program that accepts 10 numbers from the user and displays the even numbers among them.

## Files

- `src/even_numbers.cbl`: The COBOL source code for the program.

## How to Compile and Run

1. Ensure you have a COBOL compiler installed on your system.
2. Navigate to the `src` directory where the `even_numbers.cbl` file is located.
3. Compile the COBOL program using the following command:
   ```
   cobc -o even_numbers even_numbers.cbl
   ```
4. Run the compiled program with the command:
   ```
   ./even_numbers
   ```

## Dependencies

- COBOL Compiler (e.g., GnuCOBOL)

## Usage

When you run the program, it will prompt you to enter 10 numbers. After entering the numbers, it will display all the even numbers among them.