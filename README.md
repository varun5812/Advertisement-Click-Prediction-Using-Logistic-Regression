# Advertisement-Click-Prediction-Using-Logistic-Regression
Predicting whether a user will click on an online advertisement using Logistic Regression. This project applies data analysis and machine learning to optimize ad targeting and improve click-through rates (CTR).
1 Project Overview

This project builds a Logistic Regression model to predict if a user will click on an online advertisement.
It uses Python (pandas, NumPy, scikit-learn, Seaborn, Matplotlib) for data analysis, visualization, and model building.
The goal is to help digital marketers optimize their campaigns by identifying high-probability users, improving Click-Through Rate (CTR) and Return on Ad Spend (ROAS).

2 Problem Statement

Advertising companies often spend large budgets showing ads to users who are not interested.
This project aims to predict user engagement (click/no click) using a data-driven approach, helping businesses focus on the right audience.

3 Dataset Description

Dataset: advertising.csv

Feature	Description
Daily Time Spent on Site	Time (in minutes) user spends daily on the site
Age	User’s age
Area Income	Average income of the user’s area
Daily Internet Usage	Total internet usage per day
Clicked on Ad	Target variable (0 = No, 1 = Yes)
4 Model Development

Algorithm: Logistic Regression

Train–Test Split: 70:30

Libraries Used: pandas, numpy, seaborn, matplotlib, scikit-learn

Evaluation Metrics: Accuracy, Precision, Recall, F1-Score, AUC

5 Exploratory Data Analysis (EDA)

Visualizations were created to understand data patterns:

Distribution of user ages

Area income vs click behavior

Daily internet usage patterns

Correlation heatmap between variables

(You can insert your charts or screenshots here if you like)

6 Model Evaluation
Metric	Value
Accuracy	97.6%
Precision (class 0 / 1)	0.97 / 0.98
Recall (class 0 / 1)	0.98 / 0.97
AUC Score	0.991

7 Final Result:


Result Summary:

The Logistic Regression model achieved 97.6% accuracy, with nearly equal precision and recall across both classes.
The model generalizes well and performs reliably for predicting ad-click behavior.

8 Key Insights

Users spending less time on the site tend to click ads more.

Older users are more likely to click advertisements.

Area Income slightly influences ad-click probability.

The model achieved balanced performance with minimal misclassifications.

9 How to Run the Project
# 1️⃣ Clone the repository
git clone https://github.com/your-username/Advertisement-Click-Prediction.git
cd Advertisement-Click-Prediction

# 2️⃣ Install dependencies
pip install -r requirements.txt

# 3️⃣ Run the script or notebook
python advertisement_click_prediction.py
# or
jupyter notebook Advertisement_Click_Prediction.ipynb

🧾 Conclusion

This project successfully predicts advertisement clicks using Logistic Regression.
With 97.6% accuracy and an AUC of 0.991, it provides a reliable way to enhance ad targeting efficiency and optimize marketing budgets.

10 Tech Stack

Language: Python

Libraries: pandas, numpy, seaborn, matplotlib, scikit-learn

Tools: Jupyter Notebook / VS Code

11 Author

Varun Kumar H C
🎓 Data Science Trainee — EdiGlobe
📧 [varunkumar5812@gmai.com]
