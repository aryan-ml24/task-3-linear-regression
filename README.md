# Task 3 - Linear Regression

Elevate Labs AI & ML Internship

## Objective
Implement and understand **simple and multiple linear regression** using Scikit-learn, Pandas and Matplotlib.

## Dataset
`data/tips.csv` is the same tips dataset used in Task 2.

- Target: `tip`
- Simple regression feature: `total_bill`
- Multiple regression features: `total_bill`, `size`

## Evaluation
Metrics used:
- MAE (Mean Absolute Error)
- MSE (Mean Squared Error)
- R² score

### Test-set results

| Model | MAE | MSE | R² |
|---|---:|---:|---:|
| Simple Linear Regression | 0.6209 | 0.5688 | 0.5449 |
| Multiple Linear Regression | 0.6639 | 0.6486 | 0.4811 |

## Files
- `task3_linear_regression.ipynb` - complete notebook
- `data/tips.csv` - dataset
- `outputs/simple_regression.png` - regression line
- `outputs/multiple_regression.png` - actual vs predicted plot
- `outputs/model_metrics.csv` - evaluation metrics
- `requirements.txt` - Python dependencies

## How to run
```bash
pip install -r requirements.txt
jupyter notebook task3_linear_regression.ipynb
```
