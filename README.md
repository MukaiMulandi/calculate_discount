# calculate_discount
Python function called calculate_discount that performs the discount logic, along with user input and output handling.

🧮CALCULATE_DISCOUNT - PYTHON SCRIPT
This Python script defines a function calculate_discount(price, discount_percent) that computes the final price after applying a discount. It only applies the discount if it's 20% or higher; otherwise, it returns the original price.


📋FEATURES
Calculates discount based on user input.

Applies discount only when it's 20% or more.

Handles invalid (non-numeric) inputs gracefully.

Displays the final price with clear formatting.



🧑‍💻HOW TO USE
1. Make sure you have Python 3 installed.

2. Save the script in a file, for example: discount_calculator.py.

3. Run it in a terminal:
python discount_calculator.py

4. You'll be prompted to enter:

      The original price of the item.

      The discount percentage.



📄FUNCTION REFERENCE
 
def calculate_discount(price, discount_percent):

-price: The original price of the item (float or int).

-discount_percent: The discount percentage (float or int).

-Returns the final price after discount if discount_percent >= 20, otherwise returns the original price.



🛠 FUTURE IMPROVEMENTS
-Add currency selection.

-Support for bulk discount calculations.

-GUI using Tkinter or a web version with Flask.

