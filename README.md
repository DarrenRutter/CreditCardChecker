# CreditCardChecker

This program is my solution to the Codecademy 'Credit Card Checker' challenge.

The program accepts several arrays of card numbers, some valid, some invalid and some mystery.

At first, the program iterates through each card number, starting at the final digit in the array. From here, every other digit is doubled. If the doubled digit is greater than 9, 9 is subtracted and the resulting number is saved. If the doubled digit is less than 9, the resulting number is saved.

The second step is the sum of all numbers in the card number. The sum of all numbers in the card number is then divided by 10. The card is valid if the remainder following this operation is 0, or invalid otherwise.

Finally, the program prints a list of the companies from whom an invalid card number has been received.

There are comments testing the outputs throughout the program, simply uncomment these to see the results of testing.

Feel free to use and comment as needed.
