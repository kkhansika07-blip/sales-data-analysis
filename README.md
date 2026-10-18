# Sales Data Analysis

## Project Overview

This beginner-friendly data analysis project explores a small sales dataset. The goal is to clean, analyze, and visualize sales data to uncover simple but meaningful insights about products, regions, and trends.

## Tech Stack

- Python
- Pandas - Data manipulation & analysis
- NumPy - Numerical operations
- Matplotlib & Seaborn - Data visualization
- Jupyter Notebook - Interactive analysis

## Dataset

The data/sales_data.csv file contains 30 realistic sales records with the following columns:
- Order ID
- Customer Name
- Product
- Category (Electronics, Furniture, Stationery)
- Quantity
- Unit Price
- Order Date
- Region (North, South, East, West)
- Payment Method

## Installation

1. Clone this repository
2. Create a virtual environment (optional but recommended)
3. Install dependencies:
`ash
pip install -r requirements.txt
`
4. Launch Jupyter Notebook:
`ash
jupyter notebook
`

## Analysis

The notebook in 
otebooks/sales_data_analysis.ipynb covers:
- Data loading and overview
- Data cleaning & validation
- Basic statistics
- Exploratory Data Analysis (EDA)
- Visualizations (bar charts, histograms, correlation heatmap)
- Key insights & takeaways

## Key Findings

- Electronics category has higher-value products on average
- Sales are spread across different regions
- Quantity and pricing patterns vary by product category
- Simple trends can be spotted with basic visualizations

## Future Work

- Add more visualizations and insights


- Expand dataset with more rows for deeper analysis
- Add time-series analysis for monthly trends
- Include profit calculations
- Create interactive dashboards

## License

This project is licensed under the MIT License - see the LICENSE file for details.
