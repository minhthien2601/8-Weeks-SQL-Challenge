# Case Study #6: Clique Bait

<img src="https://user-images.githubusercontent.com/81607668/134615258-d1108e0d-0816-4cd7-a972-d45580f82352.png" alt="Image" width="300" height="300">

## 📚 Table of Contents
- [Business Task](#business-task)
- [Case Study Solution](#case-study-solution)
  - [1. Entity Relationship Diagram](#1-entity-relationship-diagram)
  - [2. Digital Analysis](#2-digital-analysis)
  - [3. Product Funnel Analysis](#3-product-funnel-analysis)
  - [4. Campaigns Analysis](#4-campaigns-analysis)
- [📃 What can you practice with this case study?](#what-can-you-practice-with-this-case-study)


***

## Business Task
Clique Bait is an online seafood store. 

In this case study - you are required to support the founder and CEO Danny’s vision and analyse his dataset and come up with creative solutions to calculate funnel fallout rates for the Clique Bait online store.

## Case Study Solution

### 1. Entity Relationship Diagram

[Diagram link](https://dbdiagram.io/d/634f90314709410195915552)

![Untitled (1)](https://user-images.githubusercontent.com/101379141/196609058-acb8a711-16aa-493d-912f-0b94872337e1.png)


**users table**

<img width="366" alt="image" src="https://user-images.githubusercontent.com/81607668/134623074-7c51d63a-c0a4-41e0-a6fc-257e4ca3997d.png">

**events table**

<img width="849" alt="image" src="https://user-images.githubusercontent.com/81607668/134623132-dfa2acd3-60c9-4305-9bea-6b39a9403c14.png">

**event_identifier table**

<img width="273" alt="image" src="https://user-images.githubusercontent.com/81607668/134623311-1ad16fe7-36e3-45b6-9dc6-8114333cf473.png">

**page_hierarchy table**

<img width="576" alt="image" src="https://user-images.githubusercontent.com/81607668/134623202-3158ca06-6f04-4b67-91f1-e184761e885c.png">

**campaign_identifier table**

<img width="792" alt="image" src="https://user-images.githubusercontent.com/81607668/134623354-0977d67c-fc61-4e61-90ee-f24a29682a9b.png">

***


### 2. Digital Analysis

View my solution [here](https://github.com/minhthien2601/8-Weeks-SQL-Challenge/blob/dc820e9aa1f631026586c6e122d12e727b6aaa6e/8-WEEK-SQL-CHALLENGE/Case%20Study%20%236%20-%20Clique%20Bait/2.Digital_Analysis.md).

1. How many users are there?
2. How many cookies does each user have on average?
3. What is the unique number of visits by all users per month?
4. What is the number of events for each event type?
5. What is the percentage of visits which have a purchase event?
6. What is the percentage of visits which view the checkout page but do not have a purchase event?
7. What are the top 3 pages by number of views?
8. What is the number of views and cart adds for each product category?
9. What are the top 3 products by purchases?

***

### 3. Product Funnel Analysis

View my solution [here](https://github.com/minhthien2601/8-Weeks-SQL-Challenge/blob/dc820e9aa1f631026586c6e122d12e727b6aaa6e/8-WEEK-SQL-CHALLENGE/Case%20Study%20%236%20-%20Clique%20Bait/3.Product_Funnel_Analysis.md).

Using a single SQL query - create a new output table which has the following details:

1. How many times was each product viewed?
2. How many times was each product added to cart?
3. How many times was each product added to a cart but not purchased (abandoned)?
4. How many times was each product purchased?

Additionally, create another table which further aggregates the data for the above points but this time for each product category instead of individual products.

Use your 2 new output tables - answer the following questions:

1. Which product had the most views, cart adds and purchases?
2. Which product was most likely to be abandoned?
3. Which product had the highest view to purchase percentage?
4. What is the average conversion rate from view to cart add?
5. What is the average conversion rate from cart add to purchase?

***

### 4. Campaigns Analysis

View my solution [here](https://github.com/minhthien2601/8-Weeks-SQL-Challenge/blob/dc820e9aa1f631026586c6e122d12e727b6aaa6e/8-WEEK-SQL-CHALLENGE/Case%20Study%20%236%20-%20Clique%20Bait/4.%20Campaigns_Analysis.md).

Generate a table that has 1 single row for every unique visit_id record and has the following columns:
- user_id
- visit_id
- visit_start_time: the earliest event_time for each visit
- page_views: count of page views for each visit
- cart_adds: count of product cart add events for each visit
- purchase: 1/0 flag if a purchase event exists for each visit
- campaign_name: map the visit to a campaign if the visit_start_time falls between the start_date and end_date
- impression: count of ad impressions for each visit
- click: count of ad clicks for each visit
- (Optional column) cart_products: a comma separated text value with products added to the cart sorted by the order they were added to the cart (hint: use the sequence_number)
  

***
#
## What can you practice with this case study?
- Creating Tables
- JOINS
- CTE's
- Window Functions RANK
- STRING_AGG , WITHIN GROUP 
- CASE Statements
- As well as other functions, operators and clauses
