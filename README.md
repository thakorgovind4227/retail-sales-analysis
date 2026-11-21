# Retail Sales & Business Performance Analysis

## Project Overview

This project analyzes retail sales data to understand business performance, customer behavior, product profitability, and sales trends.

Python libraries are used to inspect, process, analyze, and visualize the dataset and generate meaningful business insights.

## Objectives

- Analyze overall Sales and Profit.
- Identify top-performing categories and products.
- Evaluate regional and customer performance.
- Analyze monthly and yearly sales trends.
- Identify loss-making products and sub-categories.
- Generate business insights and recommendations.

## Tools & Technologies

- Python
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

## Dataset

**Dataset:** Sample Superstore

The dataset contains 10,194 records and 21 original columns, including order details, customer information, product categories, Sales, Quantity, Discount, and Profit.

## Project Analysis

1. Data Inspection and Cleaning
2. Feature Engineering
3. Category Analysis
4. Region Analysis
5. Sub-Category Analysis
6. Product Analysis
7. Customer Analysis
8. Time-Based Analysis
9. NumPy Statistical Analysis
10. Data Visualization
11. Business Insights and Recommendations

## Key Business Insights

- Technology generated the highest Sales and Profit among the categories.
- West was the highest-performing region.
- Copiers generated the highest sub-category Profit.
- Tables recorded the highest sub-category loss.
- Canon imageCLASS 2200 Advanced Copier ranked first in both Sales and Profit.
- 302 products generated negative Profit.
- November recorded the highest Sales across the dataset.

## Project Structure

```text
retail-sales-analysis/
│
├── data/
│   └── raw/
│       └── sample_-_superstore.xls
│
├── retail_sales_analysis.ipynb
│
└── README.md
```

## How to Run

1. Clone or download this repository.
2. Install the required libraries:

```bash
pip install pandas numpy matplotlib jupyter xlrd
```

3. Open the project folder.
4. Launch Jupyter Notebook.
5. Open `retail_sales_analysis.ipynb`.
6. Run the notebook cells in order.

## Important Note

The dataset contains 611 future-dated orders between November 21, 2026 and December 30, 2026. These records were retained because there was no evidence that they were invalid. Therefore, 2026 results should not be considered finalized full-year results.

## Conclusion

This project demonstrates practical data analysis skills using Python, including data inspection, feature engineering, exploratory data analysis, statistical analysis, visualization, and business insight generation.