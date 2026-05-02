# 🏠 PrimeEstate – House Price Prediction App

## 📌 Overview
PrimeEstate is a machine learning-based web application that estimates real estate prices based on user inputs such as location, square footage, BHK, and number of bathrooms.

The app provides not only price predictions but also simple market insights to help users understand property value positioning.

---

## ✨ Features
- Property price prediction using ML  
- Location-based estimation  
- Market comparison with similar properties  
- Price insight (fair / high / low)  
- Clean and interactive UI  

---

## 🛠️ Tech Stack
- Python  
- Streamlit  
- Scikit-learn  
- Pandas, NumPy  
- Matplotlib / Seaborn  

---

## 📂 Project Structure
House_Price_prediction/
├── .gitignore
├── app.py                   # Streamlit application

├── Bengaluru_House_Data.csv # Raw dataset
├── cleaned_df.csv           # Processed dataset

├── eda.ipynb                # Data analysis notebook

├── hdlogo.webp              # UI asset
├── house_logo.png           # UI asset

├── model_columns.joblib     # Feature columns
├── rf_model.joblib          # Trained ML model

├── README.md
├── requirements.txt

---

## ▶️ Run Locally

```bash
pip install -r requirements.txt
streamlit run app.py