# 🌍 Air Quality Index (AQI) Prediction Using Deep Learning (LSTM & CNN-LSTM)

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-DeepLearning-orange?style=for-the-badge&logo=tensorflow)
![LSTM](https://img.shields.io/badge/LSTM-Time%20Series-green?style=for-the-badge)
![CNN-LSTM](https://img.shields.io/badge/CNN--LSTM-Hybrid-red?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

## 📌 Project Overview

Air pollution has become one of the biggest environmental challenges worldwide. This project predicts the **Air Quality Index (AQI)** using Deep Learning models such as **LSTM** and **CNN-LSTM**. The models learn historical AQI patterns and forecast future AQI values, helping governments, researchers, and citizens make informed decisions.

The project includes complete data preprocessing, exploratory data analysis (EDA), model training, evaluation, and future AQI forecasting.

---

## 🎯 Objectives

- Predict Air Quality Index (AQI) using historical data.
- Compare the performance of **LSTM** and **CNN-LSTM** models.
- Perform comprehensive Exploratory Data Analysis (EDA).
- Forecast AQI for the next 30 days.
- Evaluate model performance using multiple regression metrics.

---

## 📂 Dataset

The dataset contains daily air quality information including:

- Date
- City
- AQI
- PM2.5
- PM10
- NO
- NO₂
- NOx
- NH₃
- CO
- SO₂
- O₃

After preprocessing, unnecessary values are removed and missing values are handled before model training.

---

## 🚀 Features

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- AQI Trend Visualization
- Pollution Analysis by City
- LSTM Model
- CNN-LSTM Hybrid Model
- Model Comparison
- Future AQI Forecasting
- Export Forecast Results to CSV

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## 📊 Exploratory Data Analysis

The notebook includes:

- AQI Distribution
- AQI Boxplot
- Daily AQI Trend
- Top 10 Most Polluted Cities
- Top 10 Cleanest Cities
- PM2.5 vs AQI
- PM10 vs AQI
- CO vs AQI
- O₃ vs AQI
- Delhi AQI Trend Analysis

---

## 🧠 Deep Learning Models

### 1️⃣ LSTM Model

- Two LSTM Layers
- Dropout Regularization
- Dense Layers
- Adam Optimizer
- Early Stopping
- Model Checkpointing

### 2️⃣ CNN-LSTM Model

- Conv1D Layer
- MaxPooling Layer
- LSTM Layer
- Dense Layers
- Hybrid Architecture for Time-Series Prediction

---

## 📈 Evaluation Metrics

The models are evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 📁 Project Structure

```
Air-Quality-Index-AQI-Prediction/
│
├── Air_Quality_Index_(AQI)_Prediction_Using_Deep_Learning_(LSTM_&_CNN_LSTM).ipynb
├── README.md
├── Clean_AQI_Dataset.csv
├── AQI_30_Days_Forecast.csv
├── Model_Comparison.csv
└── best_lstm.keras
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/your-username/Air-Quality-Index-AQI-Prediction.git
```

Move into the project folder

```bash
cd Air-Quality-Index-AQI-Prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook
```

or open directly in **Google Colab**.

---

## 📉 Output

The project generates:

- AQI Prediction Graphs
- Actual vs Predicted AQI
- 30-Day AQI Forecast
- Model Comparison Report
- Forecast CSV File

---

## 📌 Results

The Deep Learning models successfully learn historical AQI trends and generate accurate future AQI predictions.

The comparison demonstrates the effectiveness of both architectures for time-series forecasting, with CNN-LSTM providing enhanced feature extraction before sequential learning.

---

## 🔮 Future Improvements

- Transformer-based Forecasting
- BiLSTM Models
- GRU Networks
- Real-Time AQI Prediction
- Weather Feature Integration
- Interactive Dashboard using Streamlit
- Deployment using Flask/FastAPI

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Push the branch.
5. Open a Pull Request.

---

## 📜 License

This project is released under the MIT License.

---

## 👨‍💻 Author

**Purusottam Dash**

B.Tech CSE (Artificial Intelligence & Machine Learning)

- Python
- Machine Learning
- Deep Learning
- TensorFlow
- Data Science
- Time-Series Forecasting

---

⭐ If you found this project useful, don't forget to **Star** the repository!
