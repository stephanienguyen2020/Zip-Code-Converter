# Zip-Code-Converter
## Description

The ZIP Code Converter is a Java program designed to convert between ZIP codes and their corresponding barcodes. The program follows the encoding scheme for a five-digit ZIP code used by the U.S. Postal Service, which includes a check digit to ensure accuracy in sorting mail.

The program can perform two main functions:

1. **ZIP Code to Barcode Conversion:**
   - The user enters a five-digit ZIP code.
   - The program calculates the check digit and generates the corresponding barcode.
   - The barcode is displayed to the user using colons (:) for half bars and vertical bars (|) for full bars.

2. **Barcode to ZIP Code Conversion:**
   - The user enters a barcode representing a ZIP code.
   - The program decodes the barcode and extracts the ZIP code.
   - It verifies the correctness of the barcode format and the match of the calculated check digit.
   - If there are any errors or mismatches, the program reports them to the user.

## Files

- `ZipCode.java`: Contains the implementation of the ZIP Code Converter, including methods for barcode encoding and decoding.
- `ZipTest.java`: Provides a user-friendly command-line interface for interacting with the program. It allows users to input ZIP codes and barcodes and see the conversions.

## How to Use

1. Compile the Java source files using a Java compiler (e.g., `javac`).
2. Run the program by executing the `ZipTest` class.
3. Follow the on-screen prompts to perform ZIP code to barcode or barcode to ZIP code conversions.
   
## Error Handling

The program includes error handling to ensure that user inputs are validated and that any errors or mismatches in the barcode format or ZIP code are reported to the user.

## Future Enhancements

Future enhancements could include building a graphical user interface (GUI) application that allows users to interact with the program in a more intuitive way. This GUI application could also visually represent the barcodes.

## Credits
- Program inspired by problem P8.7 in "Big Java" by Cay S. Horstmann.

- If you encounter any issues or have suggestions for improvements, please feel free to open an issue on the GitHub repository.
