# Calorie Burn Prediction Engine 

This machine learning model predicts the number of calories burned based on user data like age, gender, heart rate, exercise duration, and body temperature.

### Dataset Used
Merged dataset of:
- `exercise.csv` — physical attributes & workout metrics
- `calories.csv` — actual calories burned

### ML Models Trained
- Linear Regression
- Decision Tree Regressor  *(Best performing model)*
- Random Forest Regressor

### Model Performance
- **Decision Tree** achieved high accuracy with low mean squared error.
- Final model exported using `pickle`.

### File(s)
- `CalorieBurnPredictionEngine.ipynb` — Full EDA + training + evaluation

### How to Use
You can clone the repo and run the notebook in Jupyter or Google Colab.

---

Ideal for fitness tracking apps, health analytics, or wearable integration.
