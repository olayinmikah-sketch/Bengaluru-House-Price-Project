# Bengaluru House Price Predictor

Predicts residential property prices in Bengaluru using Linear Regression.

## Results
- R² Score (test set): 0.84
- Cross-validated mean R² (5-fold): 0.82

## Tech Stack
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

## Project Steps
1. Data cleaning — handled missing values, parsed non-standard sqft formats
2. Feature engineering — price-per-sqft, BHK extraction, location encoding
3. Outlier removal — statistical and domain-aware methods
4. Model training — Linear Regression with GridSearchCV comparison
5. Model export — saved as pickle file for deployment

## Dataset
Bengaluru House Price dataset (13,000+ listings)
