# Assignment_3
# 💼 Salary Prediction using Polynomial Regression

## 📌 Objective

The objective of this project is to predict employee salaries based on their position level using a **Polynomial Regression** model. Since the relationship between position level and salary is nonlinear, Polynomial Regression is used to improve prediction accuracy compared to a simple Linear Regression model.

---

## 📂 Dataset Link

**Dataset Name:** Position Salaries Dataset

**Source:** https://www.kaggle.com/datasets/akram24/position-salaries

---

## 🛠️ Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- KaggleHub

---

## ⚙️ Methodology

1. Imported the required libraries.
2. Loaded the dataset using KaggleHub.
3. Explored the dataset and displayed summary statistics.
4. Checked for missing values.
5. Selected Position Level as the input feature and Salary as the target variable.
6. Split the dataset into training and testing sets (80:20).
7. Transformed the feature using Polynomial Features (Degree = 3).
8. Trained a Polynomial Regression model.
9. Predicted salaries for the test dataset.
10. Evaluated the model using MAE, MSE, and R² Score.
11. Visualized the results using scatter plots and a Polynomial Regression curve.

---

## 📊 Results

| Metric | Value |
|---------|------:|
| Mean Absolute Error (MAE) | **70635.24590164085** |
| Mean Squared Error (MSE) | **6263853282.860292** |
| R² Score | **0.8762695647830065** |

The Polynomial Regression model successfully captured the nonlinear relationship between position level and salary. The regression curve closely fits the original data points, resulting in accurate salary predictions.

---

## ✅ Conclusion

Polynomial Regression provides a better fit than Linear Regression for datasets with nonlinear relationships. In this project, the model effectively predicted employee salaries based on position level while achieving low prediction error and a high R² score. The generated regression curve demonstrates that Polynomial Regression is well suited for this dataset. However, selecting a very high polynomial degree may cause overfitting and reduce the model's ability to generalize to unseen data.

---

## 📁 Project Structure

```
Assignment-3
│── Assignment-3.ipynb
│── README.md
```

---

## ▶️ How to Run

1. Open the notebook in Google Colab.
2. Install KaggleHub:

```bash
pip install kagglehub[pandas-datasets]
```

3. Run all notebook cells.
4. View the evaluation metrics and plots.

---
