Documentation of the program:

This program is a simple billing system that allows users to view available products, calculate the bill amount for customers, and store customer details. Here is a breakdown of the program's components:

Structures:

Product: Holds information about a product, including its name, price, and quantity.

Customer: Holds information about a customer, including their name and bill amount.

Functions:

show_Products: Displays the available products and their details (name, price, and quantity).

calculate_Bill: Calculates the total bill amount for the customer based on the selected products and their quantities.

Main function:

Initializes an array of Product structures representing available products in the store. Defines variables to store the number of products, quantities, customer details, and the number of customers. Enters a while loop to display a menu and process user input until the user chooses to exit.

The menu options are: Show available products: Calls the show_Products function to display the available products.

Billing: Prompts the user to enter the customer name and select product quantities. The bill amount is calculated using the calculate_Bill function and displayed.

Customer Details: Displays the customer details, including the customer name and bill amount for each customer.

Exit: Exits the program.

The loop continues until the user enters "y" in response to the prompt to continue. This program provides a basic framework for a billing system, allowing users to view products, calculate bills, and store customer information.
