# Linear Regression Salary Prediction

This project demonstrates a **Linear Regression** model to predict employee salaries based on years of experience using the **Salary Dataset from Kaggle**.  
The complete workflow is implemented in **Google Colab** and includes clean data export and visualization.

---

## Project Overview

The objective of this project is to apply Linear Regression on a real-world dataset and evaluate model performance.  
The model is trained on the full dataset and predictions are generated for all records.

---

## Features

- Load dataset from **Kaggle ZIP file**
- Data preprocessing and inspection
- Train **Linear Regression** model
- Predict salaries for all 30 records
- Generate **clean CSV and Excel files**
- Visualize results using scatter plot
- Create a **discretized confusion matrix** (Low / Medium / High salary ranges)

---

## Dataset

**Source:** Kaggle – Salary Dataset  

**Total Rows:** 30  

**Columns:**
- `YearsExperience` – Number of years of experience
- `Salary` – Actual salary

---

## Files in This Repository

| File Name | Description |
|----------|------------|
| `Linear_Regression_Salary_Prediction.ipynb` | Google Colab notebook with full workflow |
| `salary_predictions_clean.xlsx` | Excel version of predictions |
| `README.md` | Project documentation |

---

## How to Run (Google Colab)

1. Open **Google Colab**
2. Upload `Linear_Regression_Salary_Prediction.ipynb`
3. Run cells sequentially
4. Upload the Kaggle ZIP file when prompted
5. The notebook will:
   - Extract the dataset
   - Train the model
   - Generate predictions
   - Display tables and plots
   - Download CSV and Excel files

---

## Output Generated

- 📊 Scatter plot of Actual vs Predicted salaries
- 📄 CSV file with all 30 rows
- 📄 Excel file with all 30 rows
- 📉 Confusion matrix using salary ranges

---

## Visualization

- **Blue dots:** Actual salaries  
- **Red line:** Linear Regression prediction  

The plot clearly shows the relationship between experience and salary.

---

## Confusion Matrix (Concept)

Since Linear Regression predicts continuous values, salaries are discretized into:
- Low
- Medium
- High  

This allows evaluation using a confusion matrix for academic understanding.

---

## Notes

- Entire dataset is used for prediction output
- Clean formatting is maintained for CSV and Excel
- Designed strictly for **academic submission**

---

## License

This project is intended **for educational purposes only**.
