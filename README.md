# Task-5-EDA
🚢 Titanic Survival EDA 
This repository contains a detailed Exploratory Data Analysis (EDA) of the Titanic dataset for Task 5 of the Elevate Labs Internship. The analysis aims to uncover patterns in passenger survival using statistical techniques, visual storytelling, and feature engineering.

 Project Structure:
TASK-5-EDA
│
├── Dataset/              # train.csv, test.csv, gender_submission.csv
├── Outputs/              # Final PDF report, prediction file
├── TASK_5_Titanic.ipynb  # Main Jupyter Notebook
└── README.md             # This file
📊 Highlights of the Analysis
Cleaned and imputed missing values (Age, Fare, Embarked).
Univariate analysis: Age, Fare, Sex, Pclass, Embarked, etc.
Bivariate analysis: Survival by Gender, Class, Age, Fare, Deck.
Multivariate analysis with correlation heatmaps and pairplots.
Feature engineering: Title, FamilySize, IsAlone, AgeBin, FareBin.
Rule-based prediction created and saved for testing.
🧠 Key Insights
Females had higher survival rates than males.
1st class passengers were more likely to survive.
Passengers who paid more (Fare) had better survival chances.
Being alone negatively affected survival.
Titles like Miss/Mrs showed survival differences.
🛠️ Tools Used
Python, Pandas, NumPy
Seaborn, Matplotlib
Missingno (for null visualizations)
🔗 Dataset Source
Kaggle Titanic Dataset: https://www.kaggle.com/competitions/titanic/data

👨‍💻 Author
Patel Manthan
