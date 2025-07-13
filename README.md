# Student Performance Predictor using Machine Learning

A beginner-friendly ML project that predicts a student's **final marks** based on their:
- Attendance percentage
- Daily study hours
- Previous academic performance

This project uses **synthetic data**, a **Linear Regression model**, and simple visualization to help students and educators understand performance trends.

---

## Project Overview

This notebook builds a **machine learning regression model** to estimate student performance. By simulating data and training a model, we explore how basic input features contribute to academic outcomes.

- Fully self-contained  
- No external CSVs or datasets required  
- Built to run in under 5 minutes  
- Modular, readable, and beginner-friendly  

---

## Features

- Synthetic data generator with realistic student info
- Clean preprocessing steps
- Linear Regression using `scikit-learn`
- Evaluation with MAE, MSE, and R² metrics
- Visualization of actual vs predicted marks
- Optional prediction form to try your own inputs

---

## Project Structure

```
Student_Performance_Predictor.ipynb   ← Main Jupyter Notebook
README.md                             ← You're here!
```

---

## Dependencies

Installation of the following libraries if you don't already have them:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn faker
```

---

## How to Run

1. Download the notebook: `Student_Performance_Predictor.ipynb`
2. Open it with **Jupyter Notebook**, **JupyterLab**, or **Google Colab**
3. Run all cells from top to bottom (Ctrl + F9 in Colab)
4. Optional: Input your own values to test custom predictions

---

## Model Evaluation

The model is a simple **Linear Regression**, evaluated using:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

> Accuracy varies slightly with random data, but R² typically ranges from **0.85–0.92**  
> (Decent for a toy model with just 3 features!)

---

## Try It Yourself

Change the values in the **prediction form section**:
```python
custom_attendance = 85
custom_study_hours = 4
custom_prev_marks = 75
```
...and the model will predict final marks based on those inputs!

---

## Educational Value

### For Students:
- Understand the importance of attendance, study habits, and prior effort.
- Visualize how small improvements in study hours or consistency can reflect in final grades.

### For Teachers:
- Simulate how student performance might be influenced by behavior and history.
- Use as a teaching tool for regression and ML fundamentals.

---

## License

This project is open-source and free to use for educational purposes. No real student data was used in the making of this project.
