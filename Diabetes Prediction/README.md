# 🩺 Diabetes Prediction System

This project is a Machine Learning-based web application that predicts whether a person has diabetes based on key health metrics. It uses a logistic regression model trained on the popular PIMA Indian Diabetes dataset and offers a user-friendly interface built with Gradio.

---

## 📌 Features

- Logistic Regression-based classification
- Clean Gradio web interface
- Interactive form to enter patient data
- Displays prediction with user-friendly message

---

## ⚙️ How It Works

1. The `Model.ipynb` file loads the dataset, trains a logistic regression model, and exports it as a `.pkl` file.
2. The `App.ipynb` file builds an interactive web app using Gradio.
3. Users input medical parameters like Glucose level, BMI, Insulin, Age, etc.
4. The app predicts whether the patient is likely to have diabetes.

---

## 💡 Libraries Used

- Python
- Pandas
- Numpy
- Scikit-learn
- Gradio

---

## 🖥️ Screenshot

![App Screenshot](screenshot.png)

---

## 🚀 Try It Yourself

You can run the `app.ipynb` in Google Colab or Jupyter Notebook and launch the Gradio interface.

---

