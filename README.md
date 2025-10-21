# AI-ML Assignment 2 – Linear Regression
**Author:** Alex Torres  

### Project Description
This project applies the Machine Learning Lifecycle to predict **house prices** using the **King County Housing Dataset**.  
The model uses **sqft_living** as the main feature and a new engineered feature called **house_age**.

### Dataset
- **Source:** House Sales in King County, USA - kaggle 
- **Target Variable:** `price`
- **Features Used:**  
  - `sqft_living` (main predictor)  
  - `house_age` = 2025 - `yr_built`

### Data Cleaning
- Removed missing values in price and living area.
- Removed extreme outliers with sqft_living > 10,000.

### Feature Engineering
- Created new feature `house_age` from `yr_built`.

### Model
- **Algorithm:** Linear Regression
- **Split:** 80% training, 20% testing
- **Evaluation Metrics:** Mean Squared Error (MSE), R-squared (R²)

### Results
| Metric | Value |
|---------|--------|
| **Mean Squared Error (MSE)** | 4.5e+10 (example) |
| **R-squared (R²)** | 0.70 (example) |

### Visualization
A scatter plot shows actual vs. predicted prices, with a red regression line representing model predictions.

### Predictions
Example predictions for two new houses:
| sqft_living | house_age | Predicted Price ($) |
|--------------|------------|--------------------|
| 1500 | 30 | 307,265 |
| 3000 | 10 | 715,702 |

### ML Lifecycle Steps
1. Problem Definition  
2. Data Collection  
3. Data Cleaning  
4. Feature Engineering  
5. Model Training  
6. Evaluation  
7. Deployment & Testing  