# 🏠 Bengaluru House Price Prediction

A machine learning project to predict house prices in Bengaluru based on location, square footage, number of bedrooms (BHK), and number of bathrooms. The project uses **Ridge Regression** and includes complete data preprocessing, feature engineering, outlier handling, and an optional Flask-based web interface for real-time predictions.

---

## 🚀 Features

- 📊 **Data Cleaning & Preprocessing** — Handle missing values, normalize formats, and clean raw data.
- 🛠 **Feature Engineering** — Extract features like BHK, price per sqft, and one-hot encode categorical variables.
- 🧹 **Outlier Removal** — Filter data using domain-specific rules (e.g., unrealistic area per BHK, extreme price per sqft).
- 🤖 **ML Model** — Ridge Regression with preprocessing pipeline.
- 📈 **Model Evaluation** — Achieves **R² Score: 0.87** on test data.
- 🌐 **Web App Interface (Flask)** — Users can enter property details and get instant predictions.

---

## 📂 Dataset

The dataset contains housing listings from Bengaluru and includes:

- **Location**
- **Size** (converted to BHK)
- **Total Square Feet**
- **Number of Bathrooms**
- **Price** (in lakhs)

**Source:** Kaggle (Bengaluru House Data)

---

## 🛠️ Tech Stack

- **Languages:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn
- **Development Tools:** Jupyter Notebook
- **Deployment:** Flask (optional web app)
- **Model:** Ridge Regression

---

## 📦 Installation & Usage

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Udayhrmt45/Bangalore_House_Price_Prediction.git
cd bengaluru-house-price-prediction
```
### 2️⃣ Run Jupyter Notebook for Model Training

```bash
jupyter notebook House_price.ipynb
```
This will:  
Preprocess the dataset  
Train the Ridge Regression model  
Save the model as RidgeModel.pki  

### 3️⃣ Run the Flask Web App
```bash
pip install flask
python main.py
```

Access the app at http://localhost:5000 and enter:
- Location  
- Square footage 
- BHK count   
- Number of bathrooms to get predicted price.

