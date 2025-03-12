# ☕ Coffee Sales Prediction & Analysis

## 📌 Project Overview
This project analyzes and predicts coffee sales using historical sales data. It includes data preprocessing, exploratory data analysis (EDA), feature engineering, and machine learning models (Random Forest Regressor) to forecast sales trends. The project also visualizes sales patterns across different time periods and locations.

## 📊 Features Implemented
- **Data Cleaning & Preprocessing**
  - Handled missing values
  - Extracted Month, Day, Weekday from Date
- **Exploratory Data Analysis (EDA)**
  - Sales distribution by country, category, and month
  - Time series analysis of sales trends
- **Machine Learning Model (Random Forest Regressor)**
  - Trained on extracted features
  - Evaluated model using MAE & RMSE
  - Optimized using hyperparameter tuning

## 📁 Dataset
- The dataset contains historical coffee sales data with columns such as:
  - `Date` (timestamp of sale)
  - `City` (sales location)
  - `Category` (type of coffee product)
  - `Sales` (final sales amount)

## 🚀 Installation & Setup
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/yourusername/coffee-sales-prediction.git
cd coffee-sales-prediction
```

### **2️⃣ Install Dependencies**
```bash
pip install -r requirements.txt
```

### **3️⃣ Run the Jupyter Notebook**
```bash
jupyter notebook
```
Open `coffee_sales.ipynb` to explore the analysis and model.

## 📈 Results & Insights
- **Feature Importance Analysis** shows `Month` is the most influential predictor.
- **Actual vs. Predicted Sales Scatter Plot** highlights model accuracy.
- **Residual Analysis** suggests further improvements needed.

## 🔥 Future Improvements
- Add more features (holiday, promotions, etc.)
- Test other ML models (XGBoost, LSTM for time series)
- Deploy model as an API for real-time predictions

## 📜 License
This project is open-source and available under the MIT License.

## 🤝 Contributing
Feel free to submit pull requests and suggestions!

---
💡 **Developed by [Your Name]** 🚀

