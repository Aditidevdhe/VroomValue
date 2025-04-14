# VroomValue
# 🚗 Car Price Prediction using Machine Learning

A machine learning-based web application that predicts the selling price of a used car based on various features like brand, manufacturing year, fuel type, kilometers driven, and more. This project implements multiple regression models and uses **XGBoost Regression** for final deployment due to its superior performance.

---

## 🔗 Live Demo

👉 [Click here to try the app](https://vroomvalue-stkgz6uz7c8mlwaejcbxpe.streamlit.app/)

---

## 📊 Features Used in Dataset

The dataset includes the following features:

- `Car_Name`
- `Year`
- `Selling_Price`
- `Present_Price`
- `Kms_Driven`
- `Fuel_Type`
- `Seller_Type`
- `Transmission`
- `Owner`

---

## 🧠 ML Models Applied

We applied and compared three different regression algorithms:

- **Linear Regression**
- **Random Forest Regression**
- **XGBoost Regression** ✅ *(Best Performing Model)*

After testing and comparing the models, **XGBoost Regressor** showed the highest accuracy and was selected as the final model for deployment.

---

## 🛠️ Tech Stack

### 📌 Machine Learning & Data Analysis
- `Pandas`, `NumPy` – Data handling & wrangling
- `Seaborn`, `Matplotlib` – Data visualization
- `Scikit-learn` – ML models and preprocessing
- `XGBoost` – Final ML model

### 🧹 Data Preprocessing
- Handling missing values
- Encoding categorical variables
- Feature selection and scaling
- Train-test split

### 🌐 Frontend
- Developed a **user-friendly web interface** where users can input values and instantly get predictions.
- No need to run code locally – just input and predict!

---

## 📈 Data Visualization

We used `Seaborn` and `Matplotlib` to explore the dataset and understand relationships between features. Key insights were gathered to improve model accuracy and guide feature engineering.

---

## 🚀 How It Works

1. User inputs car details through the frontend.
2. Data is passed to the backend ML model.
3. The trained **XGBoost Regressor** predicts the estimated selling price.
4. Output is displayed in real-time.

---

## 🗃️ Dataset Source

The dataset was curated with typical car resale features and formatted for regression-based modeling. *(Add source link here if available)*

---

## 📥 Installation (for local use)

```bash
git clone https://github.com/yourusername/car-price-prediction.git
cd car-price-prediction
pip install -r requirements.txt
python app.py
