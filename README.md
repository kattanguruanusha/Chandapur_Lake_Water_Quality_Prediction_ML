Chandrapur Lake Water Quality Prediction (Bengaluru)

📌 Project Overview

This project focuses on analyzing and predicting the Water Quality Index (WQI) of Chandrapur Lake, Bengaluru using Machine Learning techniques. The goal is to support environmental monitoring by identifying patterns in water quality parameters and building a predictive model that can assist researchers and authorities in decision-making.

The project follows a professional end-to-end ML workflow including data cleaning, exploratory data analysis (EDA), model experimentation, evaluation, and reporting.


---

🎯 Objectives

Analyze physicochemical and biological water quality parameters

Perform exploratory data analysis to understand trends and correlations

Build and evaluate machine learning models for water quality prediction

Compare multiple models and select the best-performing one

Present results in a clear, reproducible, and professional format

---

🗂️ Project Folder Structure

Chandrapur_Lake_Water_Quality_Prediction/
│
├── data/
│   ├── raw/                # Original raw dataset
│   └── cleaned/            # Cleaned and processed dataset
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda.ipynb
│   └── 03_model_experiments.ipynb
│
├── src/
│   ├── data_loader.py
│   ├── feature_engineering.py
│   ├── graph_builder.py
│   ├── model.py
│   ├── train.py
│   └── predict.py
├── models/
│   └── best_model.pth
│
├── outputs/
│   ├── cleaned_data.csv
│   ├── evaluation_metrics.txt
│   └── plots/
│
├── reports/
│   └── PDFs/
├── app.py
│
├── requirements.txt
├── README.md


🧠 Methodology
Data Preprocessing
Cleaning, normalization, and time-based ordering of lake data
Feature Engineering
Pollution Index computation
Seasonal (month/year) features
Graph Modeling
Industrial–lake interaction modeled using graph concepts
AI Model
Spatio-Temporal Transformer (Transformer + GNN concepts)
Forecasting
Multi-month pollution trend prediction
Visualization
Streamlit-based interactive dashboard


🧪 Technologies Used
Python
PyTorch
Transformer Architecture
Graph Neural Network Concepts
Streamlit
Pandas, NumPy, Scikit-learn
Matplotlib

📊 Outputs
- Future pollution index forecast
- Industrial source influence estimation
- Lake health risk classification
- Interactive visualization dashboard

🌍 Real-World Impact
- Enables early pollution risk detection
- Supports data-driven environmental decision-making
- Scalable for real-time IoT sensor integration
- Extendable to other urban lakes

▶️ How to Run the Project
Step 1: Download Project
Download the project ZIP and extract it.
Step 2: Open Project Folder
Copy code
Bash
cd Chandra-TransNet
Step 3: Install Dependencies
Copy code
Bash
pip install -r requirements.txt
Step 4: Run Dashboard
Copy code
Bash
streamlit run dashboard/app.py
Step 5: Open in Browser
Copy code
http://localhost:8501

📌 Internship Declaration
This project was developed as part of an internship learning program to demonstrate practical knowledge of machine learning, deep learning, and AI-based environmental monitoring systems.
👤 Author
Name: Anusha kattanguru
Role: Machine Learning Intern
Project Domain: Machine Learning
