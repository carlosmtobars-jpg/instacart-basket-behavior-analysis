# Instacart Basket Behavior Analysis

## Overview
This project analyzes Instacart order data to understand how customers build their baskets over time.  
The analysis focuses on reordering behavior, popular products and categories, and temporal patterns of shopping.

## Dataset
The dataset includes several related tables (based on the well-known Instacart dataset):

- `orders`: information about each order, user and order timing.
- `order_products`: products included in each order.
- `products`: product names and category information.
- Additional lookup tables for aisles and departments.

> Note: Raw data is not included. The notebook assumes CSV files are stored in a `data/` folder.

## Tech stack
- Python: `pandas`, `numpy`
- Visualization: `matplotlib`, `seaborn`
- Environment: Jupyter Notebook

## Business questions
1. Which products and categories are most frequently added to baskets?
2. How often do customers reorder the same items?
3. Are there clear daily or weekly patterns in ordering behavior?

## Methodology
1. Load and merge multiple tables to create an analysis-ready dataset.
2. Perform exploratory analysis of product and category frequency.
3. Analyze reorder behavior and user-level patterns.
4. Visualize temporal trends (time of day, day of week).

## Example insights
- A small subset of products accounts for a large share of all ordered items.
- Many customers show consistent reordering patterns aligned with weekly habits.
- Certain categories (e.g. fresh produce) peak at specific times, indicating opportunities for targeted offers.

## How to run
1. Clone this repository.
2. Place the Instacart CSV files into a `data/` folder.
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
