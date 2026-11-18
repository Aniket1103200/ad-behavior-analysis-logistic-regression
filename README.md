# Ad-Click Prediction with Logistic Regression

Predicts whether a website visitor will **click on an online advertisement**, based on demographic and browsing data.

> 📚 **Course project:** completed while following the Udemy course *Python for Data Science and Machine Learning Bootcamp* (Pierian Data). The dataset and task come from the course.

## Data (`advertising.csv`)
Daily Time Spent on Site · Age · Area Income · Daily Internet Usage · Ad Topic Line · City · Gender · Country · Timestamp → target: **Clicked on Ad** (1/0)

## Approach
1. Exploratory data analysis: distributions, pair plots, age vs. time on site (Seaborn)
2. Selected numerical features and split into train and test data
3. Trained a **logistic regression** model (scikit-learn)
4. Evaluated it with a classification report and a confusion matrix

## Results

| Class | Precision | Recall | F1 |
|---|---|---|---|
| No click (0) | 0.87 | 0.96 | 0.91 |
| Click (1) | 0.96 | 0.86 | 0.91 |
| **Average** | **0.91** | **0.91** | **0.91** |

## Tech
Python · pandas · NumPy · scikit-learn · Matplotlib · Seaborn · Jupyter

## Run it
```bash
git clone https://github.com/Aniket1103200/ad-behavior-analysis-logistic-regression.git
cd ad-behavior-analysis-logistic-regression
pip install -r requirements.txt
jupyter notebook ad_click_logistic_regression.ipynb
```
