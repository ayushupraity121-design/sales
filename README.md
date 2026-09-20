# Sales Data Calculator

A basic numerical data analysis tool built using Python and Jupyter Notebook for the Veda Technology internship program (AI & ML Track).

## Description
This project analyzes a collection of sales values to calculate essential business metrics, including total sales revenue, average sales value, highest sale, and lowest sale. It demonstrates foundational data analysis concepts and functional programming in Python.

## Objectives
* Understand basic numerical data manipulation using Python.
* Utilize built-in Python functions for dataset aggregation and evaluation.
* Present structured, human-readable analytical outputs.

## Features
* **Manual Dataset Creation:** Structured list handling for transaction tracking.
* **Automated Aggregation:** Employs built-in `sum()`, `max()`, and `min()` functions.
* **Custom Calculations:** Derives operational averages based on sample population length.
* **Formatted Console Output:** Displays results in a clean, professional dashboard view.

## Getting Started

### Prerequisites
* Python 3.x
* Jupyter Notebook or JupyterLab

### Running the Project
1. Clone this repository to your local machine.
2. Open your terminal or command prompt and launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open the `sales_analysis.ipynb` file.
4. Run the code cells sequentially to view the calculations and output.

## Code Preview

```python
# Create a collection of sales data
sales_data = [1200, 2500, 850, 3100, 1750, 4200, 1950, 1100]

# Calculate statistics
total_sales = sum(sales_data)
highest_sale = max(sales_data)
lowest_sale = min(sales_data)
average_sales = total_sales / len(sales_data)
```

.