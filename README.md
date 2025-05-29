## 🏠 Linear Regression: Housing Dataset

A simple implementation of **Linear Regression** using `scikit-learn` to model relationships in housing data.

### 🔄 Workflow

1. **Data Import & Preprocessing**
   Load `Housing.csv` with `pandas`, select relevant features, and check for nulls.

2. **Train-Test Split**
   Use `train_test_split` to divide the data (e.g., 80/20 split).

3. **Model Training**
   Fit a `LinearRegression` model from `sklearn.linear_model`.

4. **Evaluation**
   Assess performance using:

   * **MAE** (Mean Absolute Error)
   * **MSE** (Mean Squared Error)
   * **R²** (Coefficient of Determination)

5. **Visualization & Interpretation**
   Plot the regression line using `matplotlib`. Interpret:

   * **Intercept**: predicted value when input = 0
   * **Coefficient**: rate of change in the target per unit of input

### 📦 Requirements

```bash
pip install pandas scikit-learn matplotlib
```

---

Let me know if you'd like to include this in a Python script or Jupyter notebook too.
