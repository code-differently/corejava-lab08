# Return Ready Lab 08

* Part A - Foundations 3.2
* Part B - Foundations 3.3
* Part C - Instructor Challenge

## Part A

### Exercise 1:Chickens01

Read this story and calculate/print the totalEggs collected between Monday and Wednesday:

* Farmer Brown's chickens always lay eggsPerChicken eggs precisely at noon, which he collects that day.
* On Monday, Farmer Brown has chickenCount chickens.
* On Tuesday morning, Farmer Brown gains 1 chicken.
* On Wednesday morning, a wild beast eats half the chickens!
* How many eggs did Farmer Brown collect if he starts with :

| eggsPerChicken | chickenCount |
| -------------- | ------------ |
| 5 | 3 |
| 4 | 8 | 

#### Getting started

* Before you start coding complete the [Spiral Diagram Document](./src/main/java/com/codedifferently/labs/lab08/part_a/exercise01/documents/Exercise01SPD.docx)
* Get approval from instructor and continue.


### Exercise 2: Chickens02

Read this story and calculate/pring the required values:

* On Monday, Farmer Fred collects 100 eggs
* On Tuesday, Farmer Fred collects 121 eggs
* On Wednesday, Farmer Fred collects 117 eggs
* What is the dailyAverage of eggs collected?
* How many eggs could be expected in a 30-day monthlyAverage?
* If an egg can be sold for profit of $0.18, what is Farmer Fred's total monthlyProfit for all eggs?

#### Getting started

* Before you start coding complete the [Spiral Diagram Document](./src/main/java/com/codedifferently/labs/lab08/part_a/exercise02/documents/Exercise02SPD.docx)
* Get approval from instructor and continue.


## Part B

### Exercise 1: ShoppingCart01

* Declare and initialize the String variable custName
* Declare and initialize the String variable itemDesc
* Declare a String variable message
* Assign message a concatenated value that includes, custName, itemDesc, and a String literal, which results in a complete sentence:
	* example: "Tariq wants to purchase a Car"
* Print the message
* Your program should produce similar output:

```
Tariq wants to purchase a Car
``` 

* Before you start coding complete the [Spiral Diagram Document](./src/main/java/com/codedifferently/labs/lab08/part_b/exercise01/documents/ExerciseB01SPD.docx)
* Get approval from instructor and continue.

### Exercise 2: ShoppingCart02

#### Scenario

* Question: As customers fill their cart, how much will they pay?
* We need to represent the cart's items with a little more detail to answer this
* A ShoppingCart may need to know the following properties:
  * Item Price
  * Sales tax rate
  * Item quantity
  * Calculated total price of all items in the cart
* A ShoppingCart may need the following behaviors:
  * Print a message with its total

#### Assignment

* Declare and initialize numeric fields:
  * price (double)
  * tax (double)
  * quantity (int)
* Declare a double totalPrice:
  * Assign a value, calculated from price, tax, and quantity
* Change message to include quantity:
  * example : Tariq wants to purchase 2 Cars
* Print another message showing the total cost

Your program should produce a similar output:

```
Tariq wants to purchase 2 Cars
Total cost with tax is: $66,000.00
```
