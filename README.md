# 🌫️ NO Gas Concentration Prediction System

A full-stack machine learning project that predicts the concentration of Nitric Oxide (NO) gas in real-time using current readings from a gas sensor. The system consists of a trained ML model, a live server backend, and a user-friendly web interface for interaction.

🔗 **Live Website**: [no-prediction-website.onrender.com](https://no-prediction-website.onrender.com)  
📂 **GitHub Repository**: [NO-Prediction-Website](https://github.com/adityajoshi1362/NO-Prediction-website)

---

## 🧠 Project Overview

This project was developed to estimate the concentration of **NO gas** in a **gas mixture** by analyzing the **change in resistance** of an NO-sensitive sensor over time. The approach includes:

- Real-time dataset capturing resistance/current vs. time for gas mixtures.
- Machine Learning model trained to predict NO concentration based on sensor readings.
- Deployment of the trained model to a live server using Flask.
- Web-based interface allowing users to input:
  - Time (s)
  - Total Concentration (ppb)
  - Sensor Current (nA)
  
  and receive:
  - Estimated NO Concentration (ppb)

---

## ⚙️ Project Components

### 1. Dataset
- Real-time experimental data recorded using a sensor exposed to a gas mixture.
- Each data point includes:
  - Time (seconds)
  - Total Concentration (ppb)
  - Sensor Current (nanoamperes)

### 2. ML Model
- Preprocessing and feature engineering from raw data.
- Model trained to predict NO concentration using scikit-learn.
- Evaluation and tuning for optimized real-time performance.

### 3. Backend (Flask)
- Python Flask server hosts the trained model.
- Accepts JSON input from the frontend.
- Returns predicted NO concentration as response.

### 4. Frontend (HTML + JS)
- Simple web interface for user input.
- Sends data to backend via `fetch()` POST request.
- Displays the predicted NO value to the user.

---

## 🚀 How to Use

1. **Visit the Live Website**:  
   👉 [https://no-prediction-website.onrender.com](https://no-prediction-website.onrender.com)

2. **Enter Input Values**:
   - Time (in seconds)
   - Total concentration of gas (in ppb)
   - Current (in nA) from the sensor

3. **View Result**:  
   - The predicted NO gas concentration will be displayed on the page.

---

## 🛠️ How to Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/adityajoshi1362/NO-Prediction-website.git
   cd NO-Prediction-website
