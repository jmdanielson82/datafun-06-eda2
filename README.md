# datafun-06-eda
Module 6 Project for Data Analytics 

## Project Overview
This project sets up a Python environment for exploratory data analysis (EDA).  
The goal is to create a reproducible workflow using GitHub, a virtual environment, and Jupyter notebooks.

## Repository Setup
- Created a new GitHub repository and cloned it locally
- Added `.gitignore` and `requirements.txt` using provided templates
- Committed and pushed initial project files

## Virtual Environment
A local Python virtual environment was created for this project.

Commands used:
python -m venv .venv
.venv\Scripts\activate
python -m pip install --upgrade pip
pip install -r requirements.txt

## Data
A public, non-sensitive dataset was added to the project under the `data/` folder.
The dataset will be used later for exploratory data analysis.

## Notes
This README will be updated as the project progresses.
## Dataset Description

### Students Academic Performance Dataset
**Source:** Kaggle  
https://www.kaggle.com/datasets/sadiajavedd/students-academic-performance-dataset

**Description:**  
This dataset contains information on students’ academic performance along with demographic and educational background factors. It is commonly used to explore how variables such as gender, parental education, and test preparation relate to student outcomes.

**Number of Records:**  
1000 student records

**Columns:**

| Column Name | Description |
|------------|-------------|
| gender | Student gender |
| race/ethnicity | Student race or ethnicity group |
| parental level of education | Highest education level attained by a parent |
| lunch | Type of lunch program (standard or free/reduced) |
| test preparation course | Whether the student completed a test preparation course |
| math score | Math exam score |
| reading score | Reading exam score |
| writing score | Writing exam score |
