# 🌱 Crop Recommendation System using Machine Learning

This is a web-based machine learning project developed as part of my journey as a **Data Science student**. The goal is to recommend the most suitable crop to cultivate based on environmental conditions such as soil nutrients, temperature, humidity, pH, and rainfall.

The application is built with **Flask** and uses a trained **scikit-learn model** to make predictions. It also demonstrates how machine learning can be integrated with a web interface for real-world usability.

---

## 🚀 Project Objectives

- Build a crop recommendation system based on agricultural features.
- Train and deploy a classification model using scikit-learn.
- Deploy the model with a Flask web app to provide real-time predictions.
- Practice end-to-end ML lifecycle: preprocessing → model building → deployment.

---

## 🧠 Machine Learning Overview

- **Model**: Supervised Classification Model (e.g., RandomForest / DecisionTree / etc.)
- **Input Features**:
  - Nitrogen (N)
  - Phosphorus (P)
  - Potassium (K)
  - Temperature (°C)
  - Humidity (%)
  - pH
  - Rainfall (mm)
- **Output**: Recommended Crop (22 classes like rice, maize, banana, etc.)
- **Scalers Used**:
  - `StandardScaler` for normalization
  - `MinMaxScaler` for scaling to [0, 1] range

---

## 🖥️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core language |
| Flask | Web framework |
| scikit-learn | Model training & prediction |
| HTML/CSS + Bootstrap | Frontend UI |
| Jinja2 | Template rendering |
| GitHub | Version control and collaboration |

---

## 📁 Project Structure

crop-recommendation/
├── app.py # Flask app
├── model.pkl # Trained ML model
├── standscaler.pkl # StandardScaler object
├── minmaxscaler.pkl # MinMaxScaler object
├── requirements.txt # Python dependencies
├── Procfile # For deployment (Render/Heroku)
├── templates/
│ └── index.html # Main web page
├── static/
│ └── crop.png # Static image (optional)
└── README.md # Project documentation
