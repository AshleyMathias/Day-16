# Day-16
Coffee Machine Program ☕
This project simulates a coffee machine using an object-oriented approach. It uses modules to handle different aspects of the machine, including menu management, resource tracking, and payment processing.

Features 🌟
Menu Management: Dynamically displays drink options.
Resource Management: Tracks and verifies if there are enough ingredients to make the selected drink.
Payment Processing: Simulates a payment system and tracks profits.
Admin Controls:
report: Prints a report of current resources and profits.
off: Turns off the coffee machine simulation.
Prerequisites 📋
Python 3.x installed on your system.
Ensure the menu.py, coffee_maker.py, and money_machine.py modules are in the same directory as the main script.
How to Run the Program 🚀
Clone or download this repository.
Ensure the following files are in the directory:
menu.py
coffee_maker.py
money_machine.py
Open the main script file in your preferred Python IDE or text editor.
Run the program using:
bash
Copy
Edit
python main.py
Follow the prompts to interact with the coffee machine.
Program Flow 🔄
Start: The program welcomes the user and displays drink options dynamically.
Choose a Drink:
User selects a drink from the menu.
The program checks if there are enough resources.
Payment:
If resources are sufficient, the program requests payment.
Simulates a payment system using the MoneyMachine module.
Make Coffee:
If payment is successful, deducts resources and serves the selected drink.
Admin Features:
report: Displays the current resources and total profit.
off: Ends the coffee machine simulation.
Modules Overview 🛠️
1. Menu Module
Manages the list of available drinks.
Functions:
get_items(): Returns a string of available drink options.
find_drink(name): Returns the drink object based on user input.
2. CoffeeMaker Module
Tracks machine resources.
Functions:
report(): Prints the current resources.
is_resource_sufficient(drink): Checks if resources are enough for the drink.
make_coffee(drink): Deducts resources and prepares the drink.
3. MoneyMachine Module
Handles all payment-related functions.
Functions:
report(): Prints the current profit.
make_payment(cost): Processes payment and tracks profit.


Example Output 📖
What would you like? (espresso/latte/cappuccino): latte
Please insert coins.
How many quarters?: 10
How many dimes?: 5
How many nickels?: 0
How many pennies?: 0
Here is $0.75 in change.
Here is your latte ☕. Enjoy!

What would you like? (espresso/latte/cappuccino): report
Water: 200ml
Milk: 100ml
Coffee: 76g
Money: $2.50
