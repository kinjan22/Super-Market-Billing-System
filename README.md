# Super-Market-Billing-System
## Project overview
Design and implement a supermarket billing system using Python that effectively handles multiple billing functionalities. The system should allow for the input of multiple items, process their individual prices, and apply discounts where applicable. Using conditional statements and loops, the program should calculate the total bill, including any applicable discounts, and generate an itemized receipt for the customer. The system should be interactive and capable of handling real-time input, ensuring accuracy and clarity in the final output.

## Key Requirements
1.The system must allow for multiple items to be processed in a single transaction.
2.Conditional statements should be used to apply discounts based on criteria (e.g., total amount, item type, or promotions).
3.The program should calculate and display the subtotal, any discounts applied, and the final total amount due.
4.The itemized bill should display the name, quantity, price of each item, and the final total after discounts.
5.Loops should be utilized to handle continuous input of items until the billing process is complete.

## Features
* Item Selection – Users can enter multiple products with quantity and price.
* Real-Time Price Calculation – The system dynamically calculates the total cost.
* Discount Application – Discounts are applied based on the total purchase amount.
* Receipt Generation – Displays a structured bill with customer details, itemized pricing, discounts, and the final payable amount.
* Interactive and User-Friendly – Uses loops and conditionals for a seamless experience.

## Working
* The system greets the user with a welcome message and prompts them to enter their name and phone number.
* Users can input multiple products along with their quantity. The system retrieves the price from a predefined product list and calculates the total cost for each item.
* The total bill is dynamically updated as more items are added.
* Based on the total amount, the system applies discounts
* A detailed receipt is generated, including:
   Customer details (Name and Phone Number)
   Date & Time (Captured using the datetime module)
   Itemized List (Product Name, Quantity, Unit Price, and Total Price per item)
   Subtotal, Applied Discount, and Final Payable Amount
* The system displays a formatted bill, including store details, making it professional and easy to read.
* After completing one transaction, the system asks if another customer is in queue. If yes, it repeats the process; otherwise, it exits.
  
This interactive and user-friendly billing system ensures accuracy, efficiency, and automation, making it ideal for supermarket transactions. 
