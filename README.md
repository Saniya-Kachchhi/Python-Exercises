# Python-Exercises
Predict the house prices for streamlining the process

Question 1
In the House Prices - use information like the number of bedrooms and bathrooms to predict the price of a house. 

Create a function get_expected_cost() that has two arguments:

beds - number of bedrooms
baths - number of bathrooms
It should return the expected cost of a house with that number of bedrooms and bathrooms. Assume that:

the expected cost for a house with 0 bedrooms and 0 bathrooms is 80000.
each bedroom adds 30000 to the expected cost
each bathroom adds 10000 to the expected cost.
For instance,

a house with 1 bedroom and 1 bathroom has an expected cost of 120000, and
a house with 2 bedrooms and 1 bathroom has an expected cost of 150000

Question 2
You are thinking about buying a home and want to get an idea of how much you will spend, based on the number of bedrooms and bathrooms. You are trying to decide between four different options:

Option 1: house with two bedrooms and three bathrooms
Option 2: house with three bedrooms and two bathrooms
Option 3: house with three bedrooms and three bathrooms
Option 4: house with three bedrooms and four bathrooms
Use the get_expected_cost() function you defined in question 1 to set option_1, option_2, option_3, and option_4 to the expected cost of each option.

Question 3
You're a home decorator, and you'd like to use Python to streamline some of your work. Specifically, you're creating a tool that you intend to use to calculate the cost of painting a room.

As a first step, define a function get_cost() that takes as input:

sqft_walls = total square feet of walls to be painted
sqft_ceiling = square feet of ceiling to be painted
sqft_per_gallon = number of square feet that you can cover with one gallon of paint
cost_per_gallon = cost (in dollars) of one gallon of paint
It should return the cost (in dollars) of putting one coat of paint on all walls and the ceiling. Assume you can buy the exact amount of paint that you need, so you can buy partial gallons (e.g., if you need 7.523 gallons, you can buy that exact amount, instead of needing to buy 8 gallons and waste some paint). Do not round your answer.

Question 4
Use the get_cost() function you defined in Question 3 to calculate the cost of applying one coat of paint to a room with:

432 square feet of walls, and
144 square feet of ceiling.
Assume that one gallon of paint covers 400 square feet and costs $15. As in Question 3, assume you can buy partial gallons of paint. Do not round your answer.

Question 5
Now say you can no longer buy fractions of a gallon. (For instance, if you need 4.3 gallons to do a project, then you have to buy 5 gallons of paint.)

With this new scenario, you will create a new function get_actual_cost that uses the same inputs and calculates the cost of your project.

One function that you'll need to use to do this is math.ceil(). We demonstrate usage of this function in the code cell below. It takes as a number as input and rounds the number up to the nearest integer.

Run the next code cell to test this function for yourself. Feel free to change the value of test_value and make sure math.ceil() returns the number you expect.
