# Cereal Yield Predictions for Gambia

A machine learning project on predicting cereal yields in Gambia using 60 years of agriculture data.

## What is in the repository

- `gambia_cereal_indicators_cleaned.csv` - Final clean dataset (1961-2022)- enhanced dataset
- `Gambia_cereal_Yield_Forecasting_Model.ipynb` - Main model notebook


## The problem

Farmers in Gambia are in need of better tools to better predict the outcome of their harvest so they can plan accordingly and able meet their food security requirements.

## The solution

I developed 4 separate ML models to forecast cereal yields. The linear regression model had the best performance, successfully predicting the yield with a correctness of 64%.

**The models implemented**:
- Linear Regression (winner)
- Ridge Regression
- Random Forest
- Gradient Boosting

## Key features

- historical yield patterning (with lagged values of 1-3 years )
- moving averages of 3 year and 5 year terms
- trend and volatility indicators
- cyclical time patterns

## Results

- The model accounted for **64% of explained variation in yield**
- The output of the model indicated yields started to decline after 2010 and were beginning to show early signs of recovery 
- Historical patterning has been a good predictor of yield historically

## Next steps

- To integrate additional data to boost accuracy
- To build an API to allow real-time predictions

##Requirements

Python, Pandas, Scikit-learn, Jupyter