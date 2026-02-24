# 🚗 Car Price Prediction

A full-stack Machine Learning web application that predicts the selling price of used cars based on user input.

🌐 **Live App:** https://car-price-prediction-asz5tqlfcwm2jiappivgd2z.streamlit.app  
📦 **Backend:** FastAPI (Deployed on Render)  
🎨 **Frontend:** Streamlit (Deployed on Streamlit Cloud)

---

## 🧠 Project Overview

This project uses historical car data and a trained Random Forest Regression model to estimate the resale value of a car.

Users provide:

- Car Name
- Year of Purchase
- Present Price
- Kilometers Driven
- Fuel Type
- Seller Type
- Transmission
- Number of Owners

The system processes this data and returns a predicted selling price in lakhs.

---

## ⚙️ Tech Stack

- Python
- Scikit-learn (Random Forest Regressor)
- FastAPI (Backend API)
- Streamlit (Frontend UI)
- Render (Backend Deployment)
- Streamlit Community Cloud (Frontend Deployment)
- Git & GitHub (Version Control)

---

## 🚀 How It Works

1. User inputs car details in the Streamlit interface.
2. The frontend sends a POST request to the FastAPI backend.
3. The backend loads the trained model.
4. The model predicts the selling price.
5. The result is returned and displayed in the UI.

---


---

## 📊 Model Details

- Algorithm: Random Forest Regressor
- Library: Scikit-learn
- Task: Regression
- Output: Predicted selling price (in lakhs)

---

## 🌟 Key Features

- Clean minimal UI
- REST API architecture
- Real-time prediction
- Cloud deployment
- Production-ready structure

---

## 📈 Future Improvements

- Add model evaluation metrics (R², MAE)
- Add logging and monitoring
- Docker containerization
- CI/CD pipeline
- Model versioning

---

## 👤 Author

**Abhijit Fule**  
Aspiring Data Scientist  
GitHub: https://github.com/fuleabhijit  

---
