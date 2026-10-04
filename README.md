# Customer Shopping Behavior Analysis

## About the Project

This is a data analysis project based on customer shopping behavior.

I used Python to explore the dataset and understand things like customer types, product categories, purchase amounts, shopping channels, payment methods, returns, and monthly purchasing patterns.

The main goal was to practice data cleaning, exploratory data analysis, and data visualization and see what useful information can be found from the data.

## Tools Used

* Python
* Pandas
* NumPy
* Plotly
* Jupyter Notebook

## Dataset

The dataset contains **10,000 transactions** with information about customers, products, purchases, discounts, payment methods, delivery, returns, and other shopping-related details.

The data covers purchases from **2023 to 2024**.

## What I Did

1. Loaded and explored the dataset
2. Checked columns, data types, and missing values
3. Cleaned the data
4. Converted the purchase date into datetime format
5. Created additional columns such as month, day, customer type, and shipping-related fields
6. Analyzed customer and purchase patterns
7. Created visualizations using Plotly
8. Extracted some business-related insights from the analysis

## Some Findings

* The dataset contains **10,000 transactions**.
* Total purchase value is around **₹1.89 crore**.
* Online purchases account for about **76.79%** of the total purchase value.
* Clothing has the highest total purchase value among the categories.
* Footwear has the highest average purchase amount.
* About **74.19%** of the transactions are from returning customers.
* Clothing has the highest return rate among the three main categories.
* UPI is the most commonly used payment method.
* Puma has the highest purchase value among the brands analyzed.
* May has the highest monthly purchase value in the dataset.

## Visualizations

Some of the charts created in the project include:

* Purchase value by category
* Online vs offline purchases
* Monthly purchase trends
* Return rate by category
* Average purchase amount by category
* Top brands
* New vs returning customers
* Payment methods
* Purchase amount distribution
* Delivery time distribution

The charts are available in the `output/charts` folder.

## Project Structure

```text
customer-shopping-analysis/
│
├── data/
│   └── customer_shopping_behavior.csv
│
├── notebooks/
│   └── customer_shopping_analysis.ipynb
│
├── output/
│   └── charts/
│
├── README.md
│
└── requirements.txt
```

## How to Run

Clone the repository and install the required libraries:

```bash
pip install -r requirements.txt
```

Then open the notebook:

```text
notebooks/customer_shopping_analysis.ipynb
```

and run the cells in Jupyter Notebook.

## Future Improvements

I would like to improve this project further by:

* Creating an interactive dashboard
* Adding filters for categories and customer types
* Doing customer segmentation
* Exploring more business questions
* Deploying the project as a web application
