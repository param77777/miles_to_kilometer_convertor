# Miles to Kilometer Converter

This is a simple Python application that converts miles to kilometers using a graphical user interface (GUI) built with the `tkinter` library.

## Features
- Input miles to convert them into kilometers.
- Displays the conversion result in real-time.
- User-friendly interface with input field, labels, and a calculate button.

## Requirements
- Python 3.x
- `tkinter` library (included with standard Python installation)

## How to Run
1. Ensure you have Python installed on your system.
2. Save the Python script provided into a file named `main.py`.
3. Run the script:
   ```bash
   python main.py
   ```
4. Enter the number of miles in the input field and click **Calculate**. The result will be displayed in kilometers.


## Code Explanation
- **Input Field (`Entry`)**: Allows the user to input the number of miles.
- **Labels (`Label`)**: Display static text such as "Miles", "is equal to", and "Km".
- **Button (`Button`)**: Triggers the `miles_to_km` function to perform the conversion.
- **Functionality**: The `miles_to_km` function takes the input value in miles, converts it to kilometers using the formula `kilometers = miles * 1.609`, and updates the result label.

## Example
- Input: `5 miles`
- Output: `8 kilometers`

## License
This project is open-source and free to use. Feel free to modify it as per your needs.
