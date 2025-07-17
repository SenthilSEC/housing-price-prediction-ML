# housing-price-prediction-ML
# 🏠 Housing Price Prediction ML Project

This machine learning project predicts house prices based on features like area, number of bedrooms, bathrooms, parking, and other key factors.

---

## 📊 Dataset

- **`Housing.csv`**: The training dataset containing house features and their corresponding prices.
- **`new_houses.csv`**: New input data for which the model predicts house prices.

---

## ⚙️ Technologies Used

- Python 3.x
- Pandas
- Scikit-learn
- Matplotlib
- Google Colab / Jupyter Notebook

---

## 🔍 ML Approach

- Linear Regression model
- Feature encoding of categorical columns (yes/no, furnishingstatus)
- StandardScaler for feature normalization
- Train/test split and evaluation with R² Score, MAE, and RMSE
- Plotting Actual vs Predicted prices
- Optional: Convert predicted prices back to original price scale

---

## 📁 Files Included

| File Name                       | Description                                      |
|--------------------------------|--------------------------------------------------|
| `Housing_Price_Prediction.ipynb` | Main notebook for training and predicting prices |
| `Housing.csv`                  | Dataset used for training                        |
| `new_houses.csv`               | New input samples for price prediction           |
| `README.md`                    | Project overview and instructions                |

---

## 📈 Sample Output

Predicted prices for new houses:

| Bedrooms | Bathrooms | Area (scaled) | Predicted Price (₹) |
|----------|-----------|---------------|----------------------|
| 3        | 2         | -0.77         | ₹53,93,911           |
| 3        | 1         | -1.15         | ₹27,36,661           |
| ...      | ...       | ...           | ...                  |

---

## 💡 Future Improvements

- Try Random Forest, Gradient Boosting
- Add cross-validation
- Turn into Streamlit web app
- Deploy on cloud (Heroku, Render, etc.)

---

## 👨‍💻 Author

Built by [Your Name] using Python & 💡

