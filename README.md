# 🔧 Predictive Maintenance of Industrial Machinery

This project aims to build a machine learning-based classification model to predict failures in industrial machinery using real-time sensor data. It helps maintenance teams take **proactive** steps before breakdowns occur, minimizing downtime and improving overall system reliability.

## 📌 Problem Statement

Unexpected industrial equipment failures lead to high costs and reduced productivity. Traditional reactive maintenance fails to detect early signs of failure. This project proposes a predictive maintenance solution using machine learning to classify possible fault types **before** they happen.

## ✅ Objectives

- Predict types of failures like:
  - Tool wear
  - Overheating
  - Power-related issues
- Enable early alerts through real-time monitoring
- Improve maintenance scheduling and reduce downtime

---

## 🧠 Machine Learning Approach

### 📊 Data Collection
- Real-time sensor data (e.g., temperature, vibration, pressure, current)
- Historical logs with labeled failure types

### 🛠️ Data Preprocessing
- Cleaning and normalization
- Feature selection and engineering

### 🧪 Model Training
- Algorithm used: `Random Forest Classifier` (via Watsonx.ai on IBM Cloud)
- Evaluation metrics: `Accuracy`, `Precision`, `Recall`, `F1-score`

### ☁️ Deployment
- Deployed on IBM Cloud using Watson Studio / Watsonx.ai
- Scalable architecture, supports real-time alerting and monitoring

---

## 📈 Results

The trained model achieved high accuracy in classifying fault types. Results were validated using cross-validation techniques and visualized using output plots in the Watson Studio environment.

---

## 🚀 Future Scope

- **IoT Integration**: Real-time monitoring from edge devices
- **Advanced Models**: LSTM/CNN for better fault prediction
- **Cloud Dashboard**: Scalable monitoring for multiple machines
- **Automated Scheduling**: Maintenance recommendations based on predictions

---

## 🔗 Dataset

[Machine Predictive Maintenance Dataset (Kaggle)](https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification)

---

## 🛠️ Technologies Used

- IBM Watsonx.ai Studio
- IBM Cloud
- Python, scikit-learn
- Random Forest Classifier
- Jupyter Notebook

---

## 👤 Author

**Atharv Ugale**  
Electronics and Telecommunication Engineering  
MIT Academy of Engineering

---

## 🏅 IBM Certifications

- Getting Started with AI  
- Journey to Cloud  
- Retrieval-Augmented Generation (RAG) Lab  

---

## 📄 License

This project is for educational and research purposes. Commercial use requires permission.

---

