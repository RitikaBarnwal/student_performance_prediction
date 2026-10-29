Student Performance Prediction Using Machine Learning

About the Project

This project predicts students' final mathematics grades using Linear Regression and their study time and previous grades.

Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Google Colab

Dataset

- Source: UCI Student Performance Dataset
- Records: 395 students
- Columns: 33

Project Features

- Dataset exploration
- Missing value analysis
- Feature selection
- Train-test split
- Linear Regression model
- Actual vs predicted grade visualization
- Model evaluation
- Baseline model comparison
- Interactive prediction interface

## Model Performance

| Metric | Linear Regression | Baseline |
| --- | ---: | ---: |
| MAE | 1.27 | 3.65 |
| R² Score | 0.80 | -0.01 |

These results are from a single train-test split. The model uses previous grades, so further validation is needed before drawing broader conclusions.

How to Run

1. Open the notebook in Google Colab.
2. Upload the "student-mat.csv" dataset.
3. Run the cells in order.
4. Use the interactive interface to test predictions.

Future Improvements

- Compare multiple ML algorithms.
- Use cross-validation.
- Explore more student features.
- Improve the prediction interface.
