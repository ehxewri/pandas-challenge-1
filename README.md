# Module 4 Challenge - Python Pandas library

## Background

Welcome to the Module 4 Challenge, focused on enhancing your data analysis skills using Python's Pandas library. This challenge is designed to give you hands-on experience with real-world data analysis scenarios, including data exploration, cleaning, processing, and extracting valuable insights from large datasets. You'll be diving into a dataset from a fictional e-commerce company, addressing critical business questions such as identifying top customers, popular product categories, and calculating profits.

## Files

To get started, download the challenge files:

- [Module 4 Challenge files](#)

## Before You Begin

1. Create a new repository named `pandas-challenge-1`. Do not add this assignment to an existing repository.
2. Clone the new repository to your computer.
3. Add the downloaded starter files to your local Git repository.
4. Push the changes to GitHub or GitLab.

## Challenge Instructions

### Part 1: Explore the Data

Begin by importing the dataset from the CSV file, then explore it to understand its structure and contents:

- Import the data.
- Examine the column names.
- Gather basic statistics with the `describe` function.
- Explore the data further as needed.

**Questions to Answer with Pandas:**

- What three item categories have the most entries?
- For the category with the most entries, which subcategory has the most entries?
- Identify the five clients with the most entries.
- How many total units did the top client order?

### Part 2: Transform the Data

Transform the data for easier analysis:

- Calculate the subtotal for each line.
- Assume shipping prices based on weight.
- Include a sales tax of 9.25% for the total price.
- Calculate the cost and profit for each line.

### Part 3: Confirm Your Work

Verify your calculations against provided email receipts for three specific orders.

### Part 4: Summarize and Analyze

Use your transformed data to analyze spending by the top 5 clients:

- Calculate total spend, units purchased, shipping price, revenue, and profit.
- Create a summary DataFrame sorted by total profit.
- Format data for presentation, with currency in millions of dollars.

## Hints and Considerations

- Explore the [Pandas DataFrame documentation](https://pandas.pydata.org/pandas-docs/stable/reference/frame.html) for useful functions.
- Remember to define clear functions for repetitive tasks.
- Define your questions clearly before beginning, and ensure your code addresses these questions directly.

## Requirements

**Explore the Data (30 points):** Complete tasks related to data exploration, such as viewing column names and using the `describe` function.

**Transform the Data (30 points):** Tasks include creating columns for subtotal, shipping price, total price, cost, and profit.

**Part 3: Confirm Your Work (15 points):** Confirm the total prices for specific Order IDs match provided receipts.

**Part 4: Summarize and Analyze (25 points):** Analyze spending by the top 5 clients and present your findings in a summary DataFrame and a brief written summary.

Good luck with your challenge, and may your data analysis bring insightful findings!
