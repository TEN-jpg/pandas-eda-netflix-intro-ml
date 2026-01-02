📺 Netflix Dataset – EDA & ML (Beginner)
Project Overview

This project explores the Netflix dataset using Pandas for exploratory data analysis (EDA) and includes a basic machine learning experiment to understand the ML workflow.

The goal is learning, not building a production-ready model.

Dataset
Netflix Movies and TV Shows dataset
Columns used:
type (Movie / TV Show)
rating
release_year
date_added
listed_in
other metadata (partially cleaned)

What I Did
1. Exploratory Data Analysis (EDA)
Compared Movies vs TV Shows
Identified most common ratings
Analyzed titles added per year
Checked missing values and messy columns
Basic visualizations using Matplotlib

2. Data Cleaning
Dropped highly missing columns (e.g. director)
Handled missing dates
Converted categorical columns into numeric form (basic encoding)
Selected minimal features for ML

3. Machine Learning (Intro Only)
Built a Logistic Regression model
Split data into train/test sets

Evaluated using:
Accuracy
Confusion Matrix
Classification Report
⚠️ Model performance is not strong and that is expected — this step was only to understand the ML pipeline.

Key Learnings
How real datasets are messy
Difference between EDA vs ML thinking
Accuracy alone can be misleading
ML models need proper feature engineering and understanding

Tech Stack
Python
Pandas
Matplotlib
scikit-learn
Jupyter Notebook
