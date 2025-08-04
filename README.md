# 🚧 Predictive Maintenance of Industrial Machinery

This project implements a supervised machine learning model using **IBM Watsonx.ai** to predict **failure types in industrial machines** based on sensor data. By analyzing parameters like temperature, torque, and tool wear, the model enables industries to adopt **predictive maintenance** — reducing unplanned downtime and optimizing efficiency.

---

## 🧠 Problem Statement

Unexpected machinery failures in industrial environments lead to costly downtime and disruptions. Traditional maintenance methods are either reactive (post-failure) or preventive (scheduled), both of which may be inefficient.

This project aims to build a machine learning-based classification model that can **predict the type of failure before it occurs**, using real-time operational data from sensors.

---

## ✅ Project Objectives

* Predict specific types of machine failure:
  *Tool Wear Failure, Power Failure, Overstrain Failure, Heat Dissipation Failure, Random Failures*
* Build and train a multi-class classification model using **IBM Watsonx.ai AutoAI**
* Deploy the model as an **online API service**
* Evaluate its performance and provide future enhancement possibilities

---

## 📊 Dataset

* **Source**: [Kaggle - Predictive Maintenance Classification](https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification)
  
* **Features**:

  * Air temperature \[K]
  * Process temperature \[K]
  * Rotational speed \[rpm]
  * Torque \[Nm]
  * Tool wear \[min]
  * Product type (`L`, `M`, `H`)
    
* **Target**: `Failure Type` (Multi-class)

---

## 🧰 Tools & Technologies Used

* **IBM Cloud Lite**
* **IBM Watsonx.ai Studio**
* **AutoAI** (for no-code model training)

---

## ⚙️ System Architecture

1. Data cleaned and uploaded to IBM Watsonx.ai
2. AutoAI used to run automated model training & selection
3. Top model (Random Forest Classifier) selected and deployed
4. Online deployment tested using real-time data samples

---

## 🚀 Deployment

* Model deployed via **IBM Watsonx.ai Deployment Space**
* Available for **online testing** using JSON input of new sensor data
* Predictions include the most likely machine failure type

---

## 📈 Model Performance

* **Model Chosen**: Decision Tree Classifier
* Evaluated using:
  * Confusion Matrix
  * Classification Report
  * Real-world test cases

---

## 📷 Screenshots

* AutoAI leaderboard
* Dataset upload to Watsonx.ai
* Deployment space
* Prediction output (test)

(*See `/screenshots/` folder*)

---

## 🎓 Learning Outcomes

* Built an end-to-end machine learning solution using **cloud-based AutoML**
* Understood the application of ML in real-world industry maintenance
* Learned to deploy models and test them using cloud endpoints
* Practiced structured project documentation and presentation

---

## 🔮 Future Scope

* Integrate real-time IoT sensor feeds for live predictions
* Use advanced algorithms like Gradient Boosting, XGBoost, or LSTM
* Improve failure detection by adding more machine parameters (e.g., vibration, oil levels)
* Deploy as a dashboard for maintenance teams
* Explore edge computing for on-premise factories

---

