Student Performance Prediction using SVM

Project Overview:
This project predicts whether a student will PASS or FAIL based on two key factors: study hours and attendance percentage.
We use Support Vector Machine (SVM), a supervised machine learning algorithm, to classify students into PASS or FAIL.

Dataset:
The dataset consists of 9 students with the following features:

Study Hours	Attendance	Label
2	40	FAIL
3	45	FAIL
4	50	FAIL
5	55	PASS
6	60	PASS
7	75	PASS
8	78	PASS
9	90	PASS
10	100	PASS

Features: Study Hours, Attendance

Labels: FAIL or PASS

Model:
1.The project uses a Support Vector Machine (SVM) with a linear kernel.
2.The model learns a boundary that separates FAIL and PASS students.
3.Once trained, it can predict the result of a new student based on their study hours and attendance.

Real-Time Prediction:
The model can predict a new student’s result.
For example, a student with 11 study hours and 150 attendance is predicted to PASS, because they lie clearly in the PASS region based on the SVM boundary.

Visualization:
The data and prediction are visualized using a scatter plot:

❌ Red crosses → FAIL students

✅ Green circles → PASS students

⭐ Blue star → New student

This visualization makes it easy to see how SVM separates students and how new predictions are made.

Key Learnings:
*How to train an SVM classifier
*Understanding decision boundaries in SVM
*Predicting new data points
*Visualizing classification results effectively

Tools & Libraries:
1.Python 3
2.NumPy
3.Scikit-learn
4.Matplotlib

Author:
Ishwarya R
Department of Artificial Intelligence and Data Science
Adhiyamaan College of Engineering, Hosur, Tamil Nadu
