# House_price_prediction 

This project predicts house prices based on various features like location, number of rooms, population, and more. We use **Data Exploration, Data Preprocessing,** and **Machine Learning models** such as **Linear Regression** and Random **Forest Regression** to understand and model the data.
 
## Dataset

We use the California Housing Dataset, which includes:
- longitude, latitude
- housing_median_age
- total_rooms,total_bedrooms
- population, households
- median_income
- ocean_proximity (categorical)
- median_house_value (target)

## Technologies Used 
- python
- Pandas
- Numpy
- Matplotlib & seaborn
- Scikit-learn

## Steps Followed 
1. Loading the data 
2. Explore the data 
3. Handle missing value
4. One-hot encoding (categorical variables)
5. Feature scaling
6. Feature Engineering
7. Model Training
8. Model Evaluation

## Results

- Linear Regression R² Score: ~0.68

- Random Forest R² Score: ~0.82

Random Forest gave better predictions due to its ability to handle non-linear patterns.

## Conclusion

- Linear Regression is a good baseline model.

- Random Forest improved accuracy by learning complex relationships.

- Feature engineering and data cleaning significantly affect model performance.

## Future Improvements

- Try more models: Gradient Boosting, XGBoost

- Hyperparameter tuning using GridSearchCV

- Add cross-validation for robustness
