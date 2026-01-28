# 🎓 Student Marks Prediction Using Machine Learning and Flask

A complete end-to-end Machine Learning project that predicts **student marks based on daily study hours** and deploys the model as a **Flask web application**.

---

## 📌 Introduction

Students often invest time studying without knowing whether their effort is sufficient to achieve their academic goals. This uncertainty leads to inefficient study planning and lack of motivation.  
This project addresses that gap by using **Machine Learning** to provide a **data-driven estimation of expected marks** based on study hours.

---

## ❓ Problem Statement

Many students face the following challenges:

- No clear understanding of how study hours impact academic performance  
- Difficulty in planning daily study schedules effectively  
- Lack of simple tools that provide performance predictions using data  
- Existing solutions are either complex or not easily accessible  

There is a need for a **simple, intuitive, and data-driven system** that helps students estimate their expected marks based on the time they dedicate to studying.

---

## 🛠️ Solution Approach

This project solves the problem by building and deploying a **Machine Learning regression model** that predicts student marks using study hours as input.

### How the problem is addressed:

- 📊 **Data Collection & Analysis**  
  Historical data containing study hours and corresponding marks is analyzed to understand patterns and relationships.

- 🧠 **Machine Learning Model**  
  A **Linear Regression** model is trained using Scikit-Learn to learn the relationship between study hours and marks.

- 🌐 **Web Application Deployment**  
  The trained model is integrated into a **Flask web application**, allowing users to interact with the model through a browser.

- ✅ **Input Validation**  
  User inputs are validated to ensure realistic values (1–24 hours per day).

- 📁 **Result Storage**  
  User inputs and predicted outputs are stored in a CSV file for tracking and analysis.

  ---

## 🚀 Features

- Predicts student marks based on daily study hours  
- Clean and user-friendly web interface  
- Real-time prediction using a trained ML model  
- Input validation for reliable results  
- CSV logging of user inputs and predictions  
- End-to-end ML deployment demonstration

---

## 🧠 Machine Learning Details

- **Algorithm:** Linear Regression  
- **Input Feature:** Study Hours  
- **Output:** Predicted Marks (%)  
- **Model Training Library:** Scikit-Learn  
- **Model Serialization:** Joblib  

---

## 🛠️ Technologies Used

- Python  
- Flask  
- NumPy  
- Pandas  
- Scikit-Learn  
- Joblib  
- HTML (Jinja Templates)

---

## 📂 Project Structure
```
student-marks-prediction/
│
├── app.py                       # Flask app
├── student_mark_prediction.ipynb
├── model.pkl                    # Trained ML model
├── requirements.txt
├── README.md
├── .gitignore
│
├── templates/
│   └── index.html
│
├── static/images                       
│
└── outputs/
    └── student_info.csv    # Generated automatically 

```

---


## ⚙️ Installation & Setup

1. Clone the repository:
```
git clone https://github.com/AnjaliPanduga/student-marks-prediction.git
```
2. Navigate to the project directory:
```
cd student-marks-prediction
```
3. Install required dependencies:
```
pip install -r requirements.txt
```
4. Run the Flask application:
```
python app.py
```
5. Open your browser and visit:
```
http://127.0.0.1:5000/
```

---

👩‍💻 Author

Anjali Panduga

📧 Email: pandugaanjali2003@gmail.com

🔗 GitHub: https://github.com/AnjaliPanduga

---

  
