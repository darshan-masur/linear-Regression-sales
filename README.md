# Linear Regression - Advertising Dataset

This is one of my first machine learning projects where I explored Linear Regression using a classic advertising dataset. The goal was to understand how advertising spend across different channels affects product sales — and to get comfortable with the end-to-end ML workflow in Python.

## What this project covers

- Theory behind Simple and Multiple Linear Regression
- Understanding the Cost Function (MSE) and how it measures error
- Gradient Descent — how the model learns the best-fit line
- Exploratory Data Analysis (EDA) with visualizations
- Building a Multiple Linear Regression model with scikit-learn
- Evaluating the model using R² score, MAE, and RMSE

## Dataset

The `Advertising.csv` dataset contains 200 records of advertising budgets (in thousands of dollars) spent across three channels and the resulting sales figures.

| Column    | Description                              |
|-----------|------------------------------------------|
| TV        | Budget spent on TV ads                   |
| Radio     | Budget spent on Radio ads                |
| Newspaper | Budget spent on Newspaper ads            |
| Sales     | Units sold (target variable)             |

## Project Structure

```
Linear Regression/
├── Advertising.csv          # Dataset
├── Linear Regression.ipynb  # Main notebook with analysis and model
├── requirements.txt         # Python dependencies
└── README.md
```

## How to run

1. Clone the repository
2. Install the dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Open the notebook:
   ```
   jupyter notebook "Linear Regression.ipynb"
   ```

## Dependencies

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter

## Key Takeaways

TV advertising budget had the strongest correlation with sales, while Newspaper spending had the weakest. The Multiple Linear Regression model using all three features performed significantly better than any single-feature model, which makes sense — real-world outcomes are rarely driven by just one variable.

This project helped me get comfortable with the scikit-learn API, interpreting regression metrics, and visualizing model results.
