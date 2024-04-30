# Take-Home Assessment for Intern - Oil Desk

## Introduction

This take-home assessment is designed to gauge your proficiency in Python and programming, as these are key aspects of OilDesk Intern role. The assessment consists of 4 questions, each increasing in complexity. Aim to answer as many as you can, and ensure that your code is clean, well-commented, and accompanied by explanations of your approach and reasoning.

## Requirements

- Python 3.11.X
- Jupyter Notebook
- Pandas
- SQLAlchemy or any other SQL toolkit

## Instructions

1. Fork this repository to your GitHub account.
2. Clone the forked repository and create a `solutions/` directory.
3. Answer the questions listed below in a Jupyter Notebook under the `solutions/` directory.
4. Ensure that all code is clean, well-commented, and accompanied by explanations of your approach and reasoning.
5. Each question should be answered in a separate Jupyter Notebook.
6. Any packages you use must be added to the `requirements.txt` file 
7. Push the completed Notebooks back to your GitHub repository.
8. Share the GitHub link with us by the deadline provided.

## Additional Notes

- You are free to use any Python libraries you wish, the requirements above are purely a suggestion.
- You may find it useful to create an SQLITE database to store the data for the SQL questions.

---

## Questions

### Question 1: Python Basics and Data Manipulation
**Objective:** Demonstrate basic Python skills and data manipulation using Pandas.

**Task:**
- Load a given CSV file containing metal prices into a Pandas DataFrame.
- Filter the data to include only 'Copper' and 'Zinc' for the year 2021.
- Calculate the average price per month for each metal and plot it.

---

### Question 2: Asynchronous CRUD Operations in SQL Server
**Objective:** Basic asynchronous SQL Server interactions.

**Task:**
- Create an SQL table schema to store time-series metal prices. Include fields like `Date`, `Metal`, `Price`.
- Demonstrate basic asynchronous CRUD operations and write the 'Copper' and 'Zinc' timeseries to the database. 
- Demonsrate concurrent reads from the database hint: `asyncio.gather()`
---

### Question 3: Technical Indicators
**Objective**: Demonstrate ability to implement technical indicators. 
**Task:**
- Using the CSV file from Question 1, filter the data to include only 'Copper' and 'Zinc' for the year 2020 & 2021.
- Calculate MACD (slow/medium/fast) and RSI for each metal historically.
---
### Question 4 Backtesting:
**Task:**
- Select either the MACD or RSI indicator calculated in Question 3 and develop a simple trading strategy using the chosen indicator's BUY/SELL signals. 
- Calculate and display the cumulative Profit and Loss (PnL) over time for this strategy. 
---
### Question 5: Code Maintainability
**Objective:** Gauge understanding of maintainable code architecture.

**Task:**
- Take one of your previously written code blocks and refactor it to be more maintainable and modular. Explain your decisions.



## Submission Guidelines

1. Ensure that all code is clean, well-commented, and accompanied by explanations of your approach and reasoning.
2. Commit your Jupyter Notebook and any auxiliary files to your forked GitHub repository.
3. Submit the GitHub repository URL by the deadline.

---

Good luck!
