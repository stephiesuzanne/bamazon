This application was made using Node and mySQL workbanch, as well as some packages such require, mySQL and Console.table().

The application mocs Amazons's Website store. Running this application will first display all of the items available for sale. Include the ids, names, and prices of products for sale. Then, prompt users with two messages:

The first asks them the ID of the product they would like to buy.
The second message asks how many units of the product they would like to buy.
Once the customer has placed the order, the application checks if our store has enough of the product to meet the customer's request. If not, the app logs the phrase Out of stock!!, it prevents the order from going through and ask the user if what to chose a diferent item. If the store does have enough of the product, it fulfill the customer's order. This is; a) updating the SQL database to reflect the remaining quantity. and b) Once the update goes through, show the customer the total cost of their purchase.