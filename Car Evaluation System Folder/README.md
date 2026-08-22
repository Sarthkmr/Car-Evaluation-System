# 🚗 Car Evaluation System

## 📌 Project Overview

The **Car Evaluation System** is a Machine Learning classification project that predicts the overall evaluation of a car based on its features such as buying price, maintenance cost, number of doors, passenger capacity, luggage boot size, and safety level.

A **Decision Tree Classifier** is used to train the model and classify cars into different evaluation categories.

---

## 🎯 Objective

The main objective of this project is to build a Machine Learning model that can automatically evaluate a car based on its given features.

The model predicts one of four categories:

* `unacc` → Unacceptable
* `acc` → Acceptable
* `good` → Good
* `vgood` → Very Good

---

## 📊 Dataset

The project uses the **Car Evaluation Dataset** from the UCI Machine Learning Repository.

The dataset contains **1,728 car records** and **7 columns**.

### Features

| Feature  | Description                   |
| -------- | ----------------------------- |
| buying   | Buying price of the car       |
| maint    | Maintenance cost              |
| doors    | Number of doors               |
| persons  | Passenger capacity            |
| lug_boot | Luggage boot size             |
| safety   | Safety level                  |
| class    | Car evaluation/classification |

---

## 🛠️ Technologies Used

* Python
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn
* Joblib
* Google Colab
* Jupyter Notebook

---

## 🤖 Machine Learning Algorithm

### Decision Tree Classifier

A Decision Tree Classifier was selected because it is easy to understand and works well with categorical data after encoding.

The dataset was divided into:

* **80% Training Data**
* **20% Testing Data**

---

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Understanding
   ↓
Data Preprocessing
   ↓
Label Encoding
   ↓
Train/Test Split
   ↓
Decision Tree Training
   ↓
Model Prediction
   ↓
Model Evaluation
   ↓
New Car Prediction
   ↓
Save Model
```

---

## 📈 Model Performance

The trained Decision Tree model achieved:

**Accuracy: 98.55%**

The model was also evaluated using:

* Accuracy Score
* Classification Report
* Confusion Matrix

---

## 🚗 Sample Prediction

A sample car was provided to the trained model with the following characteristics:

```text
Buying Price: Low
Maintenance: Low
Doors: 4
Persons: 4
Luggage Boot: Big
Safety: High
```

### Prediction

```text
Car Evaluation: Very Good (vgood)
```

---

## 📁 Project Structure

```text
Car-Evaluation-System/
│
├── Car_Evaluation_System.ipynb
├── car_evaluation_model.pkl
└── README.md
```

---

## ▶️ How to Run

1. Download or clone this repository.
2. Open `Car_Evaluation_System.ipynb` using Google Colab or Jupyter Notebook.
3. Run the notebook cells in order.
4. The dataset will be loaded automatically.
5. Train the Decision Tree model.
6. Evaluate the model.
7. Test the model with a new car.

---

## 📌 Conclusion

This project demonstrates how Machine Learning can be used to classify cars based on their features.

The Decision Tree model achieved **98.55% accuracy** on the test dataset and successfully predicted the evaluation of a new car.

---

## 👨‍💻 Author

**Sarath Kumar M**

B.Tech Artificial Intelligence & Data Science
