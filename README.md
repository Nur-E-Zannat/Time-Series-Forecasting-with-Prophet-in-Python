# Time Series Sales Forecasting with Prophet

This project demonstrates time series forecasting on sales data using Python and Facebook Prophet.

## Project Overview
The goal of this project is to predict future sales values for products at different stores based on historical data. The dataset contains the following columns:

- `datetime` — timestamp of the sale  
- `product_id` — unique identifier of the product  
- `store_id` — unique identifier of the store  
- `sales_value` — sales amount  

## Steps Performed

1. **Environment Setup**  
   - Installed required libraries via terminal and notebook:
     ```bash
     !pip install prophet pandas
     ```
   
2. **Data Preparation**  
   - Loaded the CSV dataset into a Pandas DataFrame.  
   - Converted the `datetime` column into four new columns:  
     - `year`  
     - `month`  
     - `day`  
     - `ds` (concatenated date column used for Prophet)

3. **Model Training**  
   - Trained a Prophet model on the sales data to forecast future values.

4. **Visualization**  
   - Plotted the forecast and its components (trend, weekly, and yearly seasonality) for visual analysis.

## Tools and Libraries
- **Jupyter Notebook** — Interactive environment for running Python code  
- **Python** — Programming language used  
- **Pandas** — For data manipulation and preprocessing  
- **Prophet** — For time series forecasting

- Output

Forecasted sales values for the next 100 days

Visual representation of trends and seasonal components
