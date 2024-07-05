# FDS
Build a GUI application that represents a simple system that can be used by a food delivery
company to manage its clients’ information. There are 2 types of clients: customer or
restaurant. This application should provide a suitable user interface that allows a user to
select and perform the following SIX (6) operations:
1. Register A Client (Customer or Restaurant):
Register a new client (the user should be able to choose either customer or restaurant)
- Customer Registration:
Add a new customer. The user must enter the details of this customer which are:
customer id (must be 6 digits and unique for each customer), customer name,
customer home address and email address.
- Restaurant Registration:
Add a new restaurant (food vendor). The user must enter the details of this
restaurant which are: restaurant id (must be 6 digits and unique for each restaurant),
restaurant name, restaurant address, email address and lastly, a list of foods sold
(e.g., nasi lemak, mee goreng, chicken chop) and their prices. For simplicity, the user
can only input three food for each restaurant.
2. Add Customer Order:
 Add a new food order from a customer. The data that must be entered for the order is
the customer id (id of the customer that make the order), the restaurant’s name, food
ordered, date ordered. Then, the total amount to be paid (in RM) is calculated and
displayed. The system will ask for the customer’s id first before the user can enter the
the order’s data. If the customer’s id does not exist (i.e., customer hasn’t been registered
yet with operation no. 1), the system will display an appropriate error message and
terminate this operation.
Note: i) For restaurant names, the system will display only the registered restaurants
(from performing operation no. 1 above) and the user can only select one of these
restaurants.
 ii) For foods, the system will display only the foods that have been specified for the
selected restaurant.
 iii) For date ordered, the system can either obtain from the computer’s current date
or from the user input.
 iv) total amount to be paid is the total price of the food selected by the user
(assume no tax and delivery charge)

3. Search A Client (Customer or Restaurant):
Find a particular client (the user should be able to choose either customer or restaurant)
based on the id.
- If a customer is searched and found, display his/her name, home address, email
address and all the past orders information (restaurants’ names, foods ordered and
date ordered) of the customer. Lastly, display the total amount paid for all of the past
orders made by this customer.
- If a restaurant is searched and found, display its name, email address and all the food
names and prices that are sold by the restaurant.
- If the client id is not found, display an appropriate message.
4. List All Clients (Customers or Restaurants):
Display information of all registered clients (the user should be able to choose either to
display customers or restaurants). For each client, display the id, name and address.
5. Delete A Client (Customer or Restaurant):
Remove a client (the user should be able to choose either customer or restaurant) from
the system.
6. Exit:
 Terminate and exit from the system. 
