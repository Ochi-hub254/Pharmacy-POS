# Pharmacy-POS
Pharmacy Customer Interface
This is a simple Pharmacy Customer Interface program that allows customers to view available drugs, add drugs to their cart, view all drugs in their cart, view their cart details, purchase drugs, and generate a receipt. It also supports basic customer management functionality. The program is written in C++.

Features
1.Add Drug Details to Cart: The pharmacy system allows the admin to add drug details to the inventory. Each drug is assigned a unique drug code and can be added with relevant information such as drug name, supplier name, manufacturing company, and price.
2.Add Customer Details: The system allows customers to add their details, such as customer name, department (drug type), and a maximum limit of five drugs allowed in their cart.
3.View Available Drugs: Customers can view the list of all available drugs along with their details like drug code, drug name, supplier name, manufacturing company, and price. The system also displays the availability status of each drug (available or issued).
4.Add Drug to Cart: Customers can add a drug to their cart by specifying their customer ID and the drug code of the drug they want to add. If the drug is available and the customer has not reached the maximum drug limit, the drug is added to the cart.
5.View All Drugs in Cart Details: This option allows customers to view all the drugs present in their cart, along with their details.
6.View Your Cart: Customers can view their cart details, including their customer name, department, and the number of drugs left in their cart.
7.Purchase Drugs and Get Receipt: Customers can purchase the drugs in their cart. Once purchased, the status of the drug changes to "issued," and a receipt is generated, showing the customer's details and the purchased drugs along with the total amount to pay.


How to Use
-Run the program and start by entering the number of drugs you want to purchase.
-Follow the prompts to enter the details of each drug (drug name, supplier name, manufacturing company, and price) one by one.
-Then, enter the number '1' to continue and add your customer details (customer name, department/drug type) and the number of drugs you wish to purchase
-Now, you can access the main menu to perform various actions.
-Choose the respective options to view available drugs, add drugs to your cart, view all drugs in your cart, view your cart details, purchase drugs, or exit the system.
-When you purchase drugs, a receipt will be generated, displaying your details and the purchased drugs along with the total amount to pay.


Note
This program is a basic implementation of a Pharmacy Customer Interface and does not include advanced features like data persistence (database) or error handling. It is designed for learning and educational purposes. For real-world use, additional features, security measures, and data handling mechanisms would need to be implemented.
