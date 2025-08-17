# Discount Calculator

This is a simple Python program that calculates the final price after applying a discount, if the discount percentage is 20% or higher.

## Features

- Calculates the discounted price when the discount is 20% or more
- Returns the original price when the discount is less than 20%
- Handles user input with error checking for numeric values

## How to Use

1. Run the program in a Python environment
2. Enter the original price when prompted
3. Enter the discount percentage when prompted
4. The program will display either:
   - The final price after discount (if discount is 20% or higher)
   - The original price (if discount is less than 20%)

## Example Usage

```
Enter the original price: 100
Enter the discount percentage: 25
Final price after 25% discount: 75.00
```

```
Enter the original price: 50
Enter the discount percentage: 15
No discount applied. Original price: 50.00
```

## Requirements

- Python 3.x

## Error Handling

The program includes basic error handling to ensure users enter valid numeric values. If non-numeric input is provided, the program will display an error message.

## Functionality

The main function `calculate_discount(price, discount_percent)`:
- Takes price and discount percentage as parameters
- Returns the discounted price if discount is ≥20%
- Returns the original price if discount is <20%
