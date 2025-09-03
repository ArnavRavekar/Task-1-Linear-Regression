# Task-1-Linear-Regression

# 🏡 House Price Prediction using Linear Regression

This project implements a **Linear Regression model** to predict house prices using the **Ames Housing Dataset**. The model uses features such as square footage, number of bedrooms, and full bathrooms to estimate the sale price.

---

## 📁 Files

| File Name              | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| `train.csv`            | Training dataset with house features and target sale prices (`SalePrice`)  |
| `test.csv`             | Test dataset for prediction (no `SalePrice` column)                         |
| `sample_submission.csv`| Format for submission; includes `Id` and dummy `SalePrice`                  |
| `data_description.txt` | Full description of each column in the dataset                              |
| `my_submission.csv`    | 📤 Your generated predictions (created by the script)                       |

---

## 📊 Features Used

The model is trained on the following features:

- `GrLivArea`: Above ground living area (sq. ft.)
- `BedroomAbvGr`: Number of bedrooms above ground
- `FullBath`: Number of full bathrooms

---

## 🧪 Model Used

- **Linear Regression** (from `scikit-learn`)

---

## 🚀 How to Run in Google Colab

1. **Open [Google Colab](https://colab.research.google.com/)**
2. **Upload the files**:
   - `train.csv`
   - `test.csv`
   - `sample_submission.csv`
   - (optional) `data_description.txt`
3. **Copy-paste and run** the full Python script in a code cell (see `main.py`).
4. The model will:
   - Train on selected features
   - Evaluate performance using R² and MSE
   - Generate predictions on `test.csv`
   - Create `my_submission.csv` ready for download

---

## 📈 Sample Output
✅ Mean Squared Error: 1900448317.34
✅ R² Score: 0.7053

## 📤 Submission

- The script creates `my_submission.csv` in the correct format with two columns:
  - `Id`
  - `SalePrice` (predicted)

---

## 🔧 Requirements

This project runs in Google Colab, which has the following libraries pre-installed:

- `pandas`
- `scikit-learn`
- `matplotlib`
- `numpy`

---

## ✅ Optional Improvements

- Add more features like `GarageCars`, `YearBuilt`, `LotArea`
- Try advanced models (Ridge, Lasso, Random Forest, XGBoost)
- Perform feature scaling and outlier removal
- Use cross-validation and hyperparameter tuning

---

## 👤 Credits

- Dataset by [Dean De Cock](https://www.kaggle.com/datasets/prevek18/ames-housing-dataset)
- Project implemented in Python using `scikit-learn`

