# FAOSTAT Wheat Yield Prediction

## Objective

To analyze FAOSTAT wheat crop data and predict wheat yield using Linear Regression, Polynomial Regression, and Multivariate Regression.

## Dataset

The dataset is obtained from FAOSTAT and contains wheat data with the following elements:

- Area harvested
- Production
- Yield

The important columns used are:

- Year
- Yield
- Production
- Area

## Data Preprocessing

The dataset was filtered to include only Wheat.

The FAOSTAT `Element` column was used to separate:

- Yield
- Production
- Area harvested

The three datasets were then merged using Year.

The data was divided into:

- 70% Training Data
- 30% Testing Data

## 1. Linear Regression

Linear Regression was used to predict wheat yield using Year as the independent variable.

### Results

| Metric | Value |
|---|---:|
| MSE |20739.2657 |
| RMSE | 144.0113 |
| MAE | 119.5559 |
| R² | 0.9770 |

### Graph

![Linear Regression Graph](https://github.com/RiyaRiya184/Machine-Learning-/blob/main/ml%202/Images/Linear%20regression%20graph.png)

---

## 2. Polynomial Regression

Polynomial Regression with degree 2 was used to model the relationship between Year and wheat yield.

### Results

| Metric | Value |
|---|---:|
| MSE | PASTE VALUE HERE |
| RMSE | PASTE VALUE HERE |
| MAE | PASTE VALUE HERE |
| R² | PASTE VALUE HERE |

### Graph

![Polynomial Regression Graph](polynomial_regression_graph.png)

---

## 3. Multivariate Regression

Multivariate Regression was used to predict wheat yield using:

- Year
- Production
- Area harvested

### Results

| Metric | Value |
|---|---:|
| MSE | PASTE VALUE HERE |
| RMSE | PASTE VALUE HERE |
| MAE | PASTE VALUE HERE |
| R² | PASTE VALUE HERE |

### Graph

![Multivariate Regression Graph](multivariate_regression_graph.png)

---

## Model Comparison

| Model | MSE | RMSE | MAE | R² |
|---|---:|---:|---:|---:|
| Linear Regression | VALUE | VALUE | VALUE | VALUE |
| Polynomial Regression | VALUE | VALUE | VALUE | VALUE |
| Multivariate Regression | VALUE | VALUE | VALUE | VALUE |

## Future Prediction

The model was also used to predict wheat yield for **2030**.

**Predicted Yield:** PASTE VALUE HERE

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Conclusion

The three regression models were evaluated using MSE, RMSE, MAE, and R². The model with the best performance can be selected based on the evaluation metrics, particularly R² and error values.
