🏭 XAI-Powered Air Quality Prediction System for Delhi Using DCNN-LSTM

🌍 Overview

This repository presents an advanced Air Quality Prediction System focused on Delhi, leveraging a hybrid Deep Convolutional Neural Network (DCNN) and Long Short-Term Memory (LSTM) architecture. To enhance transparency and trust in the model, Explainable AI (XAI) methods like SHAP are integrated.
By accurately forecasting air pollution levels, this project supports informed decision-making, early warnings, and public health management in one of the most polluted cities in the world.

🎯 Problem Statement

Delhi faces recurring air quality crises due to factors like traffic emissions, industrial activity, construction dust, and crop-burning from neighboring states. Traditional prediction systems often lack the ability to model complex, time-dependent pollution patterns and are difficult to interpret.

This project solves that by:

Using a DCNN-LSTM hybrid model to capture both spatial and temporal trends.

Integrating SHAP-based XAI to explain the importance of different environmental features on pollutant levels.

🧪 Project Objectives

📊 Predict pollutant levels (e.g., PM2.5, PM10, NOx, CO, O3, SO2)

🧠 Use DCNN-LSTM architecture for spatiotemporal modeling

🔍 Integrate Explainable AI to interpret model decisions

📈 Analyze trends across districts in Tamil Nadu

♻️ Align with Sustainable Development Goal 13 (Climate Action)


🛠️ Tech Stack

| Category      | Tools Used                           |
| ------------- | ------------------------------------ |
| Programming   | Python 3.x                           |
| Data Handling | Pandas, NumPy                        |
| Visualization | Matplotlib, Seaborn                  |
| ML/DL         | Scikit-learn, TensorFlow/Keras       |
| XAI           | SHAP (SHapley Additive exPlanations) |
| Dev Platform  | Jupyter Notebook                     |


# Clone the repository
git clone https://github.com/Rishav1809/Air-Quality-Predication-using-DCNN-LSTM.git

cd Air-Quality-Predication-using-DCNN-LSTM

# Install required packages
pip install -r requirements.txt

# Launch the notebook
jupyter notebook
