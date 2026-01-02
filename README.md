📺 Netflix Dataset – EDA & Intro to Machine Learning
Overview

This project explores the Netflix Movies and TV Shows dataset using Pandas for exploratory data analysis (EDA) and implements a basic machine learning pipeline to understand the end-to-end workflow.

Goal: Learning data analysis and ML fundamentals — not building a production-ready model.

Dataset

Netflix Movies and TV Shows dataset.

Columns used:

type (Movie / TV Show)

rating

release_year

date_added

listed_in

Other metadata (partially cleaned)

What Was Done
1. Exploratory Data Analysis (EDA)

Compared Movies vs TV Shows

Analyzed rating distribution

Studied titles added per year

Identified missing and inconsistent values

Created basic visualizations using Matplotlib

2. Data Cleaning

Dropped highly missing columns (e.g. director)

Handled missing dates

Converted categorical features into numeric form (basic encoding)

Selected minimal features for machine learning

3. Machine Learning (Intro Level)

Built a Logistic Regression model

Split data into training and testing sets

Evaluated using:

Accuracy

Confusion Matrix

Classification Report

⚠️ Note: Model performance is limited and expected.
This step was done only to understand the ML pipeline, not optimization.

Key Learnings

Real-world datasets are messy

EDA and ML require different thinking

Accuracy alone can be misleading

Feature engineering and fundamentals matter more than algorithms

Tech Stack

Python

Pandas

Matplotlib

scikit-learn

Jupyter Notebook

Project Status

✔️ Completed as a learning project
🚧 Next focus: strengthening Pandas, NumPy, Matplotlib, and ML fundamentals
