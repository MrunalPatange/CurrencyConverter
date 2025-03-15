# Currency Converter

## Description
This is a simple currency converter program implemented in Python. The program allows users to convert between three different currencies: USD, EUR, and CAD. It ensures valid input and provides accurate conversions based on predefined exchange rates.

## Features
- Users can enter the amount they wish to convert.
- Supports conversions between USD, EUR, and CAD.
- Ensures input validation for the amount and currency selection.
- Provides accurate conversion based on predefined exchange rates.
- Displays the final converted amount in the target currency.

## How to Use
1. Run the script in a Python environment.
2. Enter the amount you want to convert (must be greater than 0).
3. Select the source currency (USD, EUR, CAD).
4. Select the target currency (USD, EUR, CAD).
5. The program will compute and display the converted amount.

## Requirements
- Python 3.x

## Installation
1. Download or clone this repository.
2. Ensure Python is installed on your system.
3. Run the script using the command:
   ```bash
   python currency_converter.py
   ```

## Example Usage
```
Enter the amount: 100
Source currency (USD/EUR/CAD): USD
Target currency (USD/EUR/CAD): EUR
100.0 USD is equal to 85.00 EUR
```

## Exchange Rates Used
The program uses the following predefined exchange rates:
- **USD → EUR** = 0.85
- **USD → CAD** = 1.25
- **EUR → USD** = 1.18
- **EUR → CAD** = 1.47
- **CAD → USD** = 0.80
- **CAD → EUR** = 0.68

## Notes
- The program does not fetch live exchange rates.
- If the source and target currencies are the same, the amount remains unchanged.
- Users must enter a valid positive amount and choose a correct currency option.

## License
This project is open-source and free to use.

## Author
Developed by Mrunal Patange.

