# Retail Sales — SQL Analysis

A data analysis project built around a retail sales dataset, using SQL queries inside a Jupyter notebook to explore sales patterns and extract business insights.

---

## Overview

Retail sales data tends to be messy and spread across multiple dimensions — products, customers, dates, and categories. This project digs into a real-world retail dataset and answers meaningful business questions using structured SQL queries, all from within a Python environment.

---

## Files

| File | Description |
|------|-------------|
| `sql_query.ipynb` | Main analysis notebook with SQL queries and results |
| `SQL - Retail Sales Analysis_utf .csv` | Raw retail sales dataset |

---

## What the Notebook Covers

The notebook uses SQLite (via Python) to run queries directly against the dataset and answer questions like:

- **Sales performance** — total revenue, average order value, and sales over time
- **Customer behavior** — who the top customers are and how often they purchase
- **Product & category breakdown** — which categories and products drive the most revenue
- **Time-based trends** — identifying peak sales periods by month or season
- **Exploratory queries** — filtering, grouping, and aggregating to surface patterns in the data

---

## Dataset

The CSV file contains retail transaction records with fields covering transaction ID, date, customer ID, gender, age, product category, quantity, price per unit, and total amount. It serves as the single source of truth for all queries in the notebook.

---

## Tools Used

- **Python** — pandas, sqlite3
- **SQL** — queries written and executed inside the notebook
- **Jupyter Notebook**

---

## Getting Started

1. Clone the repo
2. Open `sql_query.ipynb` in Jupyter
3. Run the cells top to bottom — the notebook loads the CSV into an in-memory SQLite database and runs all queries from there