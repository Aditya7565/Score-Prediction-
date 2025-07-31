# IPL Score Prediction Project

This project predicts the final score of an IPL cricket match innings using machine learning models. It uses match data, performs data cleaning and preprocessing, and compares multiple regression models to select the best one for score prediction.

## Features

- Data cleaning and preprocessing (removal of irrelevant columns, filtering teams, handling missing values)
- Feature encoding (Label Encoding, One-Hot Encoding)
- Correlation analysis and visualization
- Model training and evaluation:
  - Decision Tree Regressor
  - Linear Regression
  - Random Forest Regressor
  - Lasso Regression
  - Support Vector Machine (SVR)
  - Neural Network (MLPRegressor)
- Model comparison and visualization
- Score prediction function for new match situations

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Usage

1. Place your dataset at `D:\all file\data1.csv\data.csv` or update the path in the notebook.
2. Open and run the notebook `research2(1).ipynb` in Jupyter or VS Code.
3. Follow the notebook cells to:
   - Load and clean the data
   - Encode features
   - Train and evaluate models
   - Compare model performances
   - Use the `predict_score` function to predict scores for custom scenarios

## Example Prediction

```python
score = predict_score(
    batting_team='Mumbai Indians',
    bowling_team='Kings XI Punjab',
    overs=12.3,
    runs=113,
    wickets=2,
    runs_last_5=55,
    wickets_last_5=0
)
print(f'Predicted Score : {score}')
```

## Results

The notebook provides accuracy and error metrics for each model, and visualizes their performance for easy comparison.

## License

This project is for
