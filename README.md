# Feature-scalling-and-Model-comparison# California House Price Prediction – Feature Scaling & Model Comparison

AI/ML internship Task 2 (Maincrafts Technology). The project compares three regression models on the California Housing dataset after feature scaling.

## Dataset
California Housing dataset (scikit-learn): 20,640 records, 8 features (MedInc, HouseAge, AveRooms, AveBedrms, Population, AveOccup, Latitude, Longitude). Target: median house value.

## Workflow
1. Load the dataset and inspect it
2. Split into train (80%) and test (20%)
3. Scale features with `StandardScaler` (fitted on training data only to avoid data leakage)
4. Train Linear Regression, Ridge Regression (alpha=1.0) and Decision Tree (max_depth=5)
5. Evaluate with RMSE and R² on the test set
6. Select the best model and plot actual vs predicted prices

## Results
| Model | RMSE | R² |
|---|---|---|
| Linear Regression | 0.7456 | 0.5758 |
| Ridge Regression | 0.7456 | 0.5758 |
| **Decision Tree** | **0.7242** | **0.5997** |

## Files
- `AI_ML_Task2_Model_Comparison.ipynb` – full code and outputs
- `AI_ML_Task2_Report.pdf` – short report (methodology, results, conclusion)

## Tech Stack
Python, pandas, NumPy, scikit-learn, matplotlib, Jupyter Notebook..
