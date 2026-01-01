# 📊 Student Score Prediction using Linear Regression

This repository contains a **Jupyter Notebook** that demonstrates how to use **Linear Regression** to predict a student's exam score based on the number of hours studied. This project is designed as a **beginner-friendly machine learning example** using Python.

---

## 📌 Project Overview

Predicting student performance is a common real-world problem in education analytics.  
In this project, we use **Simple Linear Regression** to model the relationship between:

- **Hours Studied (independent variable)**
- **Student Score (dependent variable)**

The goal is to understand how study time affects performance and to make predictions for unseen data.

---

## 📂 Repository Structure

📦 linear-regression-for-prediction-student-score  
 ┣ 📄 student_score_pred.ipynb — Main notebook (data loading, visualization, training, prediction)  
 ┗ 📄 student_scores.csv — Dataset used for training and testing

---

## 📥 Dataset

The dataset contains two columns:

- **Hours**: Number of hours studied  
- **Scores**: Student exam score  

Example format:

Hours | Scores  
------|--------
2.5   | 21  
5.1   | 47  
9.2   | 93  

The dataset is small and ideal for learning and visualizing linear regression concepts.

---

## 🛠️ Technologies Used

- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  
- Jupyter Notebook  

---

## ⚙️ Requirements

Install the required libraries using:

pip install numpy pandas matplotlib scikit-learn jupyter

---

## 🚀 How to Run the Project

1. Clone the repository  
   git clone https://github.com/oussemachihi70-blip/linear-regression-for-prediction-student-score.git

2. Open the project folder  
   cd linear-regression-for-prediction-student-score

3. Launch Jupyter Notebook  
   jupyter notebook student_score_pred.ipynb

4. Run the cells step by step

---

## 📈 Model Workflow

The notebook covers:
- Loading and exploring the dataset  
- Visualizing data using scatter plots  
- Splitting data into training and testing sets  
- Training a Linear Regression model  
- Making predictions  
- Visualizing regression line and results  

---

## 📊 Results

The trained linear regression model successfully predicts student scores based on study hours and visualizes the relationship clearly using graphs.

---

## 💡 Future Improvements

- Add multiple features (multivariate regression)  
- Improve evaluation using RMSE and R² score  
- Deploy the model using a web interface  
- Add cross-validation  

---

## 📜 License

This project is open-source and free to use for educational purposes.

---

## 🙌 Acknowledgements

This project is inspired by beginner machine learning tutorials and educational datasets used to teach regression concepts.

---

⭐ If you find this project helpful, feel free to star the repository!
