# Receipt Generator

## Overview

This Python script generates a formatted receipt for a grocery store transaction. The script includes store details, a list of purchased items, subtotal calculations, tax application, and a grand total. The receipt also displays the cashier's name, date, and time of purchase.

## Features

- Displays store name, location, and contact information.
- Lists purchased items with their respective prices.
- Calculates and displays subtotal, tax (6%), and grand total.
- Prints the cashier's name and transaction timestamp.
- Shows a return policy message and a thank-you note.

## Installation

1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/receipt-generator.git
   ```
2. Navigate to the project directory:
   ```sh
   cd receipt-generator
   ```
3. Ensure you have Python installed (Python 3 recommended).

## Usage

Run the script using the following command:

```sh
python receipt_generator.py
```

## Example Output

```
**************************************************
				Super Market Z
				Noida, Uttar Pradesh
				(+91)555-1234
==================================================
				Cashier: Vibhu Raj
2024-02-02				15:30:45
==================================================
GROCERY

SGM SPAGHETTI SAUCE					$4.99
SGM SPAGHETTI PASTA					$1.99
...
--------------------------------------------------
Subtotal 						   $23.87
Food Tax @ 6% 					   $1.43
GRAND TOTAL  					   $25.30
==================================================
TOTAL NUMBER OF ITEMS SOLD = 		   8

No returns on meat, produce, milk products.
		Thank you for your business!!
```

## Customization

You can modify the script to:

- Change store details (name, address, phone number).
- Adjust tax rates.
- Add more items dynamically.

## Author

Mitansh

## Contributions

Feel free to submit pull requests or report issues in the repository.

