# 💰 Salary Prediction with Linear Regression

A machine learning project that predicts employee salaries based on years of experience — covering the full ML workflow from data loading and preprocessing to model training, evaluation, and export.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikit-learn)
![Jupyter](https://img.shields.io/badge/Notebook-Google%20Colab-yellow?logo=googlecolab)

---

## 🎯 Project Goal

Build a Linear Regression model that accurately predicts salary from years of experience, then evaluate and visualize the results — demonstrating a clean, end-to-end supervised ML pipeline.

---

## 🔍 What This Project Covers

- Data loading and preprocessing from a real-world Kaggle dataset
- Training a Linear Regression model using Scikit-Learn
- Generating and exporting predictions for all records (CSV + Excel)
- Visualizing Actual vs Predicted salaries with a scatter plot + regression line
- Evaluating continuous predictions using a discretized confusion matrix (Low / Medium / High salary bands)

---

## 📊 Dataset

**Source:** [Kaggle – Salary Dataset](https://www.kaggle.com/)  
**Size:** 30 records  
**Features:**

| Column | Description |
|---|---|
| `YearsExperience` | Years of professional experience |
| `Salary` | Annual salary (target variable) |

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python | Core language |
| Scikit-Learn | Model training & evaluation |
| Pandas / NumPy | Data manipulation |
| Matplotlib | Visualization |
| Google Colab | Development environment |

---

## 📁 Repository Structure
```
├── linear_regression.ipynb       # Full ML workflow notebook
├── salary_full_predictions.xlsx  # Predicted vs actual results (Excel)
└── README.md
```

---

## ▶️ How to Run

1. Open [Google Colab](https://colab.research.google.com/)
2. Upload `linear_regression.ipynb`
3. Run all cells sequentially
4. Upload the Kaggle ZIP file when prompted
5. The notebook will train the model, generate predictions, and produce all output files automatically

---

## 📈 Results & Output

- **Scatter plot** — Actual salaries (blue dots) vs. Linear Regression line (red) — shows strong positive correlation between experience and salary
- **Excel export** — Clean predictions for all 30 records with actual vs. predicted columns
- **Confusion matrix** — Salary ranges discretized into Low / Medium / High bands for classification-style evaluation of a regression model

---

## 💡 Key Takeaways

- Linear Regression performs well on this dataset due to the near-linear relationship between experience and salary
- Discretizing continuous predictions into ranges is a practical technique for communicating model accuracy to non-technical stakeholders
- Small datasets (n=30) are sufficient for demonstrating core ML concepts but would require more data for production-level confidence intervals

---

## 👤 Author

**Muhammad Anas Nadeem** — BSAI Student, CUST Islamabad  
[LinkedIn](https://www.linkedin.com/in/muhammadanas-nadeem-970300354) · [GitHub](https://github.com/anass-nadeem)

---

## 📜 License

MIT License — feel free to use or build on this project.
