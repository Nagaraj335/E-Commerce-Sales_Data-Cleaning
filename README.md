# E-Commerce Sales Analysis

This project analyzes sales data from an e-commerce platform using Python. It includes data cleaning, exploration, and output generation to provide insights into customer behavior, product performance, and sales trends.

## Project Structure

```
data/
  raw_data/                # Original datasets
  cleaned_data/            # Cleaned datasets
notebooks/
  Datacleaning1.ipynb      # Jupyter notebook for data cleaning
outputs/
  cleaned_*.csv            # Output files after processing
scripts/                   # (Reserved for Python scripts)
```

## Data Sources
- `olist_customers_dataset.csv`
- `olist_geolocation_dataset.csv`
- `olist_order_items_dataset.csv`
- `olist_order_payments_dataset.csv`
- `olist_order_reviews_dataset.csv`
- `olist_orders_dataset.csv`
- `olist_products_dataset.csv`
- `olist_sellers_dataset.csv`
- `product_category_name_translation.csv`

## How to Use
1. **Data Cleaning:**
   - Open `notebooks/Datacleaning1.ipynb` in Jupyter Notebook or VS Code.
   - Run the cells to clean and preprocess the raw data.
   - Cleaned data will be saved in `data/cleaned_data/` and `outputs/`.

2. **Analysis:**
   - Use the cleaned datasets for further analysis, visualization, or modeling.

## Requirements
- Python 3.8+
- Jupyter Notebook
- pandas, numpy, matplotlib, seaborn (install via `pip install -r requirements.txt` if available)

## Outputs
- Cleaned CSV files in `outputs/` and `data/cleaned_data/`.
- Graphs and charts generated from the analysis are saved in the `outputs/` folder.

## License
This project is for educational and analytical purposes.

## Author
Nagaraj S Navada
