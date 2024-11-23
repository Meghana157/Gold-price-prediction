# Gold-price-prediction
## Project Objective
The objective of this project is to predict gold prices (GLD) based on financial and economic indicators such as S&P 500 Index (SPX), Oil Prices (USO), Silver Prices (SLV), and Exchange Rates (EUR/USD). The project aims to leverage machine learning techniques to provide reliable predictions and gain insights into the factors influencing gold prices.

## Dataset Overview
The dataset contains daily historical data of financial indicators:

- Date: The date of observation.
- SPX: S&P 500 Index, representing the stock market performance.
- GLD: Gold price (Target variable).
- USO: Crude oil prices.
- SLV: Silver prices.
- EUR/USD: Exchange rate of Euro to US Dollar.

## Project Workflow
### Data Preprocessing:
- Checked for missing values and outliers.

### Exploratory Data Analysis (EDA):

- Visualized trends in gold prices and other financial indicators.
- Analyzed correlations between GLD and other features.
  
### Model Selection:

- Selected Random Forest Regressor for its ability to handle non-linear relationships and feature importance evaluation.
### Model Training:

- Split the data into training (80%) and testing (20%) sets.
  
### Model Evaluation:

Assessed the model's performance using the metrics such as R-squared (R²), MSE, RMSE.

## Key Insights
**Correlations:**
- Positive correlation between GLD and SLV, indicating linked market trends.
- Negative correlation between GLD and SPX, suggesting gold as a safe-haven asset during market downturns.

**Feature Importance:**
- SPX and EUR/USD have the highest influence on gold price predictions, followed by SLV.
  
**Trend Analysis:**
- Gold prices tend to increase during periods of market uncertainty and economic instability.

## Results and Model Performance
**Best Model:**  Random Forest Regressor.
**Evaluation Metrics:**
MAE: 1.31
RMSE: 1.14
R²: 0.98
The model successfully captured the non-linear relationships in the data, providing robust and accurate predictions.

## Conclusion
This project demonstrates that machine learning, particularly Random Forest Regressor, can effectively predict gold prices based on economic and financial indicators. Accurate predictions can help investors and policymakers make informed decisions in a volatile market.
<a href="">Project</a>


## How to Run the Project
**Clone the repository:**
git clone https://github.com/Meghana157/Gold-price-prediction.git  
**Install the required dependencies:**
pip install -r requirements.txt  
**Open and execute the Jupyter Notebook:**
jupyter notebook  







