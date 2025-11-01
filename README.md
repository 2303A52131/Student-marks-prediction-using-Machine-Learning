Student Marks Prediction using Machine Learning

A simple Linear Regression project that predicts student marks based on the number of courses taken and study time.  
Built using Python, Pandas, Scikit-learn, Matplotlib, and Seaborn.

Features
- Predicts marks based on study time and courses  
- Visualizes correlations and predictions  
- Evaluates model performance (MSE, R²)  
- Beginner-friendly and easy to run locally  


 Tech Stack
- Python 3.x
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/Student-Marks-Prediction-ML.git
   cd Student-Marks-Prediction-ML
2.Run the project:
  ```bash
pip install -r requirements.txt
python student_marks_predictor.py
```
Usage

Make sure the dataset student_marks.csv is in the same folder as the Python file.

Run the project — it will:

Load and display the dataset

Train a Linear Regression model

Evaluate model performance

Show a visualization and prediction sample

Example:
python student_marks_predictor.py


Output:
Dataset Loaded Successfully!
Model Performance:
Mean Squared Error (MSE): 3.72
R² Score: 0.984
Predicted Marks for (5 courses, 6.5 hrs): 36.45


Output Visualizations

Correlation Heatmap — Shows the relationship between study time, courses, and marks

Actual vs Predicted Marks Plot — Displays how well the model predicts real marks


Future Enhancements

Deploy the model online

Compare performance with Polynomial Regression or Random Forest Regression
