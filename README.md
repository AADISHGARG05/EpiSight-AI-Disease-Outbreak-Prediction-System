# 🦠 EpiSight AI – Disease Outbreak Prediction System

An end-to-end AI-powered system that predicts disease outbreak risk based on mobility trends and growth rate using machine learning models.

---

## 🌐 Live Demo

Frontend - https://episight-ai-h4z8.onrender.com/
Backend - https://episight-ai.onrender.com/

---

## 🚀 Features

* 📊 Predicts outbreak case count using real-world mobility data
* 🤖 Uses multiple ML models (Linear Regression, Random Forest, Decision Tree, Gradient Boosting)
* ⚡ Built using PySpark for big data processing
* 🌐 Flask backend API for real-time predictions
* 💻 Interactive frontend (HTML, CSS, JavaScript)
* 📉 Risk classification: Low / Medium / High

---

## 🧠 Machine Learning

* Feature Engineering using mobility data
* Models Used:

  * Linear Regression
  * Decision Tree
  * Random Forest
  * Gradient Boosting (Best Model)
* Evaluation Metrics:

  * RMSE
  * MAE
  * R² Score
* Final Model: Gradient Boosting Regressor

---

## 🛠 Tech Stack

* Python, PySpark (Big Data Processing)
* Scikit-learn (ML Models)
* Flask (Backend API)
* HTML, CSS, JavaScript (Frontend)
* Render (Deployment)

---

## ⚙️ Project Structure

```
Big_Data_Project/
│
├── backend/        # Flask API + trained model
├── frontend/       # UI (HTML, CSS, JS)
├── spark/          # Data preprocessing & model training
├── data/           # Dataset files
```

---

## 📌 How It Works

1. User inputs mobility + growth rate
2. Frontend sends request to Flask API
3. Backend loads trained ML model
4. Model predicts case count
5. Result displayed with risk level

---

## 📊 Example Output

* Predicted Cases: 31.2 Million
* Risk Level: HIGH 🔴


---

## 💡 Future Improvements

* Add time-series forecasting (LSTM)
* Region-wise predictions
* Visualization dashboards
* Real-time data integration

---

## 👨‍💻 Author

**Aadish Garg**

* GitHub: https://github.com/AADISHGARG05
* LinkedIn: https://www.linkedin.com/in/aadish-garg/

---

## ⭐ If you like this project, give it a star!
