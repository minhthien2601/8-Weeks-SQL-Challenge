# 🍕 Case Study #2 - Pizza Runner

- To read all about the case study and access the data: [Click Here!](https://8weeksqlchallenge.com/case-study-2/)

#
<img width="300" src="https://user-images.githubusercontent.com/94410139/158215978-83465a74-7ccf-457a-8770-f1bdaa0b5343.png">

## 📚 Table of Contents
- [Introduction](#introduction)
- [Cleaning](#cleaning)
- [Case Study Question](#questions)
  - [A. Pizza Metrics](#a-pizza-metrics-n)
  - [B. Runner And Customer Experience](#b-runner-and-customer-experience)
  - [C. Ingredient Optimisation](#c-ingredient-optimisation)
  - [D. Pricing and Ratings](#d-pricing-and-ratings)
- [What can you practice with this case study?](#what-method-do-you-apply-with-case-study-2)

## Introduction
Did you know that over 115 million kilograms of pizza is consumed daily worldwide??? (Well according to Wikipedia anyway…)

Danny was scrolling through his Instagram feed when something really caught his eye - “80s Retro Styling and Pizza Is The Future!”

Danny was sold on the idea, but he knew that pizza alone was not going to help him get seed funding to expand his new Pizza Empire - so he had one more genius idea to combine with it - he was going to Uberize it - and so Pizza Runner was launched!

Danny started by recruiting “runners” to deliver fresh pizza from Pizza Runner Headquarters (otherwise known as Danny’s house) and also maxed out his credit card to pay freelance developers to build a mobile app to accept orders from customers.

## Data 

<img width="500" src="https://user-images.githubusercontent.com/94410139/158216376-6b51187b-95ec-48f0-9c58-e912d9f1b035.png">


## Cleaning 
Before going through questions of Case Study #2. We need to clean database ('null' values, strings,etc ...). And some new table for specific questions.

- [Cleaning_Data Here](https://github.com/minhthien2601/8-Weeks-SQL-Challenge/blob/d43faf783545d22507b6d57eaa452317710e9607/8-WEEK-SQL-CHALLENGE/Case%20Study%20%232%20-%20Pizza%20Runner/Data_Cleaning.md)

## Questions

This case study has LOTS of questions - they are broken up by area of focus including:

### A. Pizza Metrics : 
- [Solution](https://github.com/minhthien2601/8-Weeks-SQL-Challenge/blob/d43faf783545d22507b6d57eaa452317710e9607/8-WEEK-SQL-CHALLENGE/Case%20Study%20%232%20-%20Pizza%20Runner/A.Pizza_Metric.md)
1. How many pizzas were ordered?
2. How many unique customer orders were made?
3. How many successful orders were delivered by each runner?
4. How many of each type of pizza was delivered?
5. How many Vegetarian and Meatlovers were ordered by each customer?
6. What was the maximum number of pizzas delivered in a single order?
7. For each customer, how many delivered pizzas had at least 1 change and how many had no changes?
8. How many pizzas were delivered that had both exclusions and extras?
9. What was the total volume of pizzas ordered for each hour of the day?
10. What was the volume of orders for each day of the week?
#
### B. Runner and Customer Experience
- [Solution](https://github.com/minhthien2601/8-Weeks-SQL-Challenge/blob/d43faf783545d22507b6d57eaa452317710e9607/8-WEEK-SQL-CHALLENGE/Case%20Study%20%232%20-%20Pizza%20Runner/B.Runner_and_Customer_Experience.md)
1. How many runners signed up for each 1 week period? (i.e. week starts 2021-01-01)
2. What was the average time in minutes it took for each runner to arrive at the Pizza Runner HQ to pickup the order?
3. Is there any relationship between the number of pizzas and how long the order takes to prepare?
4. What was the average distance travelled for each customer?
5. What was the difference between the longest and shortest delivery times for all orders?
6. What was the average speed for each runner for each delivery and do you notice any trend for these values?
7. What is the successful delivery percentage for each runner?

#
### C. Ingredient Optimisation
- [Solution](https://github.com/minhthien2601/8-Weeks-SQL-Challenge/blob/d43faf783545d22507b6d57eaa452317710e9607/8-WEEK-SQL-CHALLENGE/Case%20Study%20%232%20-%20Pizza%20Runner/C.Ingredient_Optimisation.md)
1. What are the standard ingredients for each pizza?
2. What was the most commonly added extra?
3. What was the most common exclusion?
4. Generate an order item for each record in the customers_orders table in the format of one of the following:
      - Meat Lovers
      - Meat Lovers - Exclude Beef
      - Meat Lovers - Extra Bacon
      - Meat Lovers - Exclude Cheese, Bacon - Extra Mushroom, Peppers
5. Generate an alphabetically ordered comma separated ingredient list for each pizza order from the customer_orders table and add a 2x in front of any relevant ingredients
      - For example: "Meat Lovers: 2xBacon, Beef, ... , Salami"
6. What is the total quantity of each ingredient used in all delivered pizzas sorted by most frequent first?

#
### D. Pricing and Ratings
- [Solution](https://github.com/minhthien2601/8-Weeks-SQL-Challenge/blob/d43faf783545d22507b6d57eaa452317710e9607/8-WEEK-SQL-CHALLENGE/Case%20Study%20%232%20-%20Pizza%20Runner/D.%20Pricing_and_Ratings.md)
1. If a Meat Lovers pizza costs $12 and Vegetarian costs $10 and there were no charges for changes - how much money has Pizza Runner made so far if there are no delivery fees?
2. What if there was an additional $1 charge for any pizza extras?
      - Add cheese is $1 extra
3. The Pizza Runner team now wants to add an additional ratings system that allows customers to rate their runner, how would you design an additional table for this new dataset - generate a schema for this new table and insert your own data for ratings for each successful customer order between 1 to 5.
4. Using your newly generated table - can you join all of the information together to form a table which has the following information for successful deliveries?
      - customer_id
      - order_id
      - runner_id
      - rating
      - order_time
      - pickup_time
      - Time between order and pickup
      - Delivery duration
      - Average speed
      - Total number of pizzas
5. If a Meat Lovers pizza was $12 and Vegetarian $10 fixed prices with no cost for extras and each runner is paid $0.30 per kilometre traveled - how much money does Pizza Runner have left over after these deliveries?

#
## What method do you apply with Case Study #2?

- Data Cleaning
- Creating Tables
- JOINS
- Aggregate Functions including STRING_AGG()
- CTE's
- CASE Statements
- Subqueries
- String Functions like CONCAT() 

