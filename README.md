# Property Prediction Model in São Paulo

This project uses Machine Learning techniques to predict the price of properties in the city of São Paulo, based on public data from April 2019. The proposal is to apply a supervised regression model, going through all the stages of a data science pipeline: cleaning, transformation, exploratory analysis, model training and evaluation.

# Dataset
- Font: https://www.kaggle.com/datasets/argonalyst/sao-paulo-real-estate-sale-rent-april-2019
- Columns removed: `Property Type, Negotiation Type, New`.
### Transformations applied:
- Conversion of the `District` column into dummy variables.  
- Handling missing values.  
- Adjust scale and encoding where necessary.

# Techniques and Models
- Models tested: **Linear Regression, Random Forest, Gradient Boosting**
- Chosen model: **Gradient Boosting Regressor**, with hyperparameter optimization
### Metrics used:
- MAE (Mean Absolute Error)
- RMSE (Root Mean Square Error)
- R² (Coeficiente de Determinação)

 
