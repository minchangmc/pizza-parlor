## Spec

Describe Pizza()
Test: It will have 3 different attributes that can be used over and over again.
Code:
Pizza(size, toppings) {
  this.size = size
  this.toppings = toppings
}
Const myPizza = new Pizza("medium", ["pepperoni","olives"], 10);
Expected Output:
 myPizza.size;
 "medium"

Describe Pizza.prototype.price
Test: It will take the size of the pizza and topping of a pizza and add them together for the price.
Code:
const newPizza = new Pizza("medium", ["pepperoni"])
const cost = 10
newPizza.price(cost);
Expected Output:
{
  size: "medium"
  toppings: "pepperoni"
  cost: 10
}