# Netflix Movies & TV Shows — EDA + Intro to Machine Learning

This project explores the **Netflix Movies and TV Shows dataset** using **Pandas** for exploratory data analysis (EDA) and implements a **basic machine learning pipeline** to understand the end-to-end ML workflow.

> **Goal:** Learning data analysis and machine learning fundamentals — **not** building a production-ready model.

---

## Dataset

**Netflix Movies and TV Shows dataset**

The dataset contains metadata about movies and TV shows available on Netflix, including content type, ratings, release year, genres, and more.

---

## Columns Used

- `type` — Movie or TV Show  
- `rating` — Content rating (TV-MA, TV-14, PG-13, etc.)  
- `release_year` — Year the title was released  
- `date_added` — Date the title was added to Netflix  
- `listed_in` — Genres (comma-separated)  
- Other metadata (partially cleaned)

---

## What Was Done

### 1. Exploratory Data Analysis (EDA)

- Compared **Movies vs TV Shows** distribution
- Identified **most common content ratings**
- Analyzed **titles added per year**
- Checked for **missing values and messy columns**
- Performed **basic visualizations** using Matplotlib

---

### 2. Data Cleaning

- Dropped columns with heavy missing values (e.g. `director`)
- Handled missing `date_added` values
- Converted date columns to datetime format
- Encoded categorical columns into numeric form (basic encoding)
- Selected **minimal features** for ML experimentation

---

### 3. Machine Learning (Intro Only)

- Built a **Logistic Regression** model
- Selected features:
  - `rating`
  - `release_year`
- Target variable:
  - `type` (Movie / TV Show)
- Split data into **training and testing sets**
- Evaluated model using:
  - Accuracy
  - Confusion Matrix
  - Classification Report

⚠️ **Note:** Model performance is intentionally basic and not strong — this step exists only to understand the ML pipeline, not to optimize predictions.

---

## Key Learnings

- Real-world datasets are **messy**
- EDA and ML require **different ways of thinking**
- Accuracy alone can be misleading
- Feature selection and encoding matter
- Understanding the workflow is more important than model performance at this stage

---

## Tools Used

- Python
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Project Status

✅ Completed as a **learning project**  
📌 Future improvements may include better feature engineering and deeper ML exploration after strengthening fundamentals.

---

