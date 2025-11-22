Marks Predictor using Linear Regression
---------------------------------------

This is a beginner-friendly Machine Learning project that predicts a student's
marks based on the number of hours they study. The project demonstrates the
fundamental ML workflow including dataset creation, model training, evaluation,
and making predictions.

Features:
- Simple and easy dataset
- Linear Regression model
- Train/Test splitting using scikit-learn
- Evaluation using MAE and MSE
- Graph of regression line using Matplotlib
- User input to get predicted marks

Tech Stack:
- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

Dataset:
Hours Studied vs Marks Obtained
1 -> 20
2 -> 30
3 -> 35
4 -> 45
5 -> 50
6 -> 60
7 -> 65
8 -> 78
9 -> 90

Project Structure:
marks_predictor.py     - Main code file
README.txt             - Documentation
requirements.txt       - Dependencies (optional)

How to Run:
1. Install the required libraries:
   pip install numpy pandas scikit-learn matplotlib

2. Run the script:
   python marks_predictor.py

3. Enter your study hours when prompted to get a predicted score.

Model Output:
- Actual vs Predicted values
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Regression line plot
- Predicted marks for user input

Example:
Input: 5 hours
Output: Predicted Marks: ~52

Future Improvements:
- Add GUI using Tkinter or Streamlit
- Use a larger real-world dataset
- Add more features (sleep hours, revision time, etc.)
- Save and load the model using joblib

This project is ideal for beginners starting with ML fundamentals.
