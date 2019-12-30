This application was made using Node and mySQL workbanch.

The application is setup similar to Amazon.com. Running this application will first display all of the items available for sale including their ids, names, and prices of products. Then, it prompt users with two messages:

The first asks them the ID of the product they would like to buy.
The second message asks how many units of the product they would like to buy.
Once the customer has placed the order, the application checks if our store has enough of the product to meet the customer's request. If not, the app informs the customer and prevents the order from going through. It then asks the user to choose a diferent item. If the store does have enough of the product, it fulfill the order. This  updates the SQL database to reflect the remaining quantity & shows the customer the total cost of their purchase once the update goes through.