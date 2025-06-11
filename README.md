# Health-Monitoring-System
This project was developed as part of the Microsoft AI and Azure 4-Week Internship Program by Edunet Foundation. It involves building a machine learning-based health monitoring system that analyzes sensor data to predict patient health conditions.

## Project Overview
This project aims to build a **Health Monitoring System** that predicts a patient's health condition as **Low**, **Medium**, or **High** based on data collected from physiological sensors. It applies **Machine Learning algorithms** to classify patient health status for better and faster diagnosis.

## Features
- Accepts input data like ECG, temperature, and pressure
- Predicts health condition using trained ML models
- Visualizes data with charts and correlation plots
- Compares performance of different algorithms
- User-friendly and easy to test with new patient data

## Technologies Used
- **Python** (Jupyter Notebook)
- **Pandas, NumPy** for data preprocessing
- **Matplotlib, Seaborn** for data visualization
- **Scikit-learn** for machine learning models

## Machine Learning Algorithms
- Logistic Regression
- Naive Bayes
- Decision Tree Classifier
- Support Vector Machine (SVM)

## Dataset
The dataset (`iot_dataset.csv`) contains:
- ECG values
- Temperature readings
- Blood pressure data
- Patient ID
- Health condition labels (Low, Medium, High)

## Results
- Output includes model accuracy, confusion matrix, and classification reports
- Real-time input accepted for live predictions
- Visual comparison of all algorithm performances

## How to Run
1. Clone the repository
2. Open `IoTFile.ipynb` in Jupyter Notebook
3. Run the cells in order
4. Input patient data at the end to get a prediction

## Author
**Kallem Teja Sree**

## References
- [IEEE Paper on Health Monitoring Using ML](https://ieeexplore.ieee.org/document/9354116)
- [ScienceDirect: IoT-Based Patient Monitoring](https://www.sciencedirect.com/science/article/pii/S2352914822001749)
- [IEEE: Real-Time Health Monitoring](https://ieeexplore.ieee.org/document/9146168)
