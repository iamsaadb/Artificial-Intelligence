For the first function "addition" I just had to return the sum of the two arguments
For the second file, I went through the list and checked if the fruit exists: 
if it exists, I calculated the cost by multiplying the weight by the cost per pound 
and I returned the cost to the total cost
in case the fruit doesn't exist, the program returns None

The total cost then is returned in case all the fruits exist.
For the third implementation, I introduced a variable fShop that was initialized by 
the first element of the list fruitShops, then I traverse the fruitShops and compare the total
price of my order, if the price in Shop A < Shop B, then my fShop gets assigned the cheapest 
shop, and so on until I traverse the whole list of fruitShops, then return the shop with the 
cheapest cost!
