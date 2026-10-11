# Sales Forecasting: Predictive Analytics

A machine-learning project exploring how historical sales data can be used to estimate future demand and support business planning.

## Project Overview

The project works with historical sales records, prepares date-based features, and trains a Linear Regression baseline. It is intended to demonstrate a practical forecasting workflow, from data preparation to model evaluation.

Forecasts are estimates, not guarantees. Model performance should be assessed against a suitable time-ordered test set and compared with a simple baseline.

## Technologies

- Python
- Pandas and NumPy
- scikit-learn
- Matplotlib and Seaborn

## Workflow

1. **Data preparation:** parse order dates and inspect missing or invalid values.
2. **Feature engineering:** derive time-related features such as year, month, day of week, and weekend indicators.
3. **Model training:** fit a Linear Regression baseline.
4. **Evaluation:** assess predictions on a time-ordered holdout set to reduce the risk of leaking future information into training.
5. **Visualisation:** compare actual and predicted values and review forecast trends.

## Reported Baseline Result

The earlier project notes report a Mean Absolute Error (MAE) of **1614.74**. Treat this as a project-reported result until it is reproduced from the current notebook and its exact data split. MAE is expressed in the target variable's units, so it should be interpreted alongside the typical sales value and a baseline model.

## Getting Started

The repository's notebook and dataset folders are the best starting points. To run the analysis locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/Don-Sanvura/Sales_Forecasting.git
   cd Sales_Forecasting
   ```

2. Install the libraries used by the notebook:

   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn jupyter
   ```

3. Launch Jupyter and open the forecasting notebook:

   ```bash
   jupyter notebook
   ```

Check the notebook for the exact dataset path and execution order. Do not commit private or licensed data without permission.

## Potential Improvements

- Compare Linear Regression with a naïve or seasonal baseline.
- Report MAE alongside RMSE and an appropriate scaled metric.
- Plot residuals and inspect performance across different time periods.
- Save reproducible evaluation results and document the forecast horizon.
- Add a tested requirements file and a sample dataset where permitted.

## Author

**Don Sanvura**  
[GitHub profile](https://github.com/Don-Sanvura) · [LinkedIn](https://www.linkedin.com/in/don-sanvura)
