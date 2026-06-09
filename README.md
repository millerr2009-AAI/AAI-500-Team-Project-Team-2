AAI-500 Team Final Project
Apartment Rental Price Classification
Project Status: Active

Project Objective
This project is part of the AAI-500 course in the Applied Artificial Intelligence Program at the University of San Diego. The goal of this project is to analyze apartment rental listings from across the United States and build a machine learning model that classifies listings into rental price categories: Low, Medium, or High.

The project also aims to compare baseline, linear, and non-linear classification models to determine which approach performs best for apartment rental price classification.

Team Members
Russell Miller - EDA & Visualization Lead, GitHub/Repo Manager

Alvaro Folgueria - Data Engineering Lead, Report Assembly Support

Raul Muollo-Diaz - Modeling & Evaluation Lead, QA Support

Project Overview
This project analyzes 99,826 apartment rental listings from across the USA to classify apartments into price categories (Low/Medium/High) based on features such as location, size, bedrooms, bathrooms, and amenities.

The project is being developed as an end-to-end team analysis that includes dataset selection, data cleaning, exploratory data analysis, model development, model comparison, and final reporting.

Dataset
Source:
UCI Machine Learning Repository
Name:
Apartment for Rent Classified
Records:
99,826
Features:
21
Target:
Price category (Low / Medium / High)
Citation:
Apartment for Rent Classified [Dataset]. (2019). UCI Machine Learning Repository. https://doi.org/10.24432/C5X623

Methods Used
Data Cleaning and Preparation

Descriptive Statistics

Exploratory Data Analysis

Data Visualization

Feature Engineering

Multiclass Classification

Model Comparison

Technologies
Python

Jupyter Notebook

pandas

numpy

matplotlib

scipy

scikit-learn

ucimlrepo

Git

GitHub

Project Description
The project uses the Apartment for Rent Classified dataset from the UCI Machine Learning Repository. The dataset contains apartment listing information such as category, bathrooms, bedrooms, fee status, photo availability, pets allowed, square footage, city, state, latitude, longitude, and price.

The team is exploring how well apartment listing features can predict rental price category. The current modeling approach uses three target classes: low, medium, and high price tiers. The project compares a majority-class baseline model, a Logistic Regression classifier, and a Random Forest classifier.

The main questions being explored are:

Which apartment listing features are most useful for predicting rental price category?

How much better do machine learning models perform compared with a simple baseline?

Which classification model provides the best balance of accuracy and class-level performance?

Current challenges include documenting the cleaning pipeline clearly, selecting the strongest features for modeling, and preparing the final report and presentation for both technical and non-technical audiences.

Project Structure
text
AAI-500-Team-Project/
├── data/
│   ├── raw/          # Original data
│   └── processed/    # Cleaned data
├── notebooks/        # Jupyter notebooks
│   ├── Team_Project_W1.ipynb
│   ├── Team_Project_W2.ipynb
│   └── Team_Project_W3.ipynb
├── README.md
└── .gitignore
Milestones
Week 1 (May 20-26): Dataset selection and repository setup

Week 2 (May 27-Jun 2): Data cleaning and preparation

Week 3 (Jun 3-9): EDA, target definition, baseline modeling, and model comparison

Week 4 (Jun 10-16): Final model refinement and report development

Week 5 (Jun 17-22): Final technical report and presentation submission

Project Progress So Far
Week 1 Completed
Selected the Apartment for Rent Classified dataset from UCI.

Defined the project goal as apartment rental price classification.

Created the initial GitHub repository structure.

Added the first version of the project README.

Assigned team roles and responsibilities.

Week 2 Completed
Loaded and inspected the full apartment rental dataset.

Reviewed dataset dimensions, columns, and basic summary statistics.

Cleaned the apartment data for downstream analysis.

Prepared a working cleaned dataset for modeling.

Organized project files for reuse in later notebooks.

Week 3 Completed
Created rental price tiers: low, medium, and high.

Evaluated class balance for the new target variable.

Selected modeling features and removed target leakage fields.

Performed a stratified train/test split.

Encoded categorical variables for machine learning.

Built a majority-class baseline model.

Trained and evaluated Logistic Regression.

Trained and evaluated Random Forest.

Compared model performance using confusion matrices, classification reports, accuracy, and macro F1.

Current Results
The current model comparison shows clear improvement over the baseline approach:

Baseline model: Accuracy = 0.58, Macro F1 = 0.24

Logistic Regression: Accuracy = 0.61, Macro F1 = 0.61

Random Forest: Accuracy = 0.85, Macro F1 = 0.83

At this stage, Random Forest is the strongest model and is the leading candidate for the final project report.

Getting Started
# Clone repository
git clone https://github.com/YOUR-USERNAME/AAI-500-Team-Project.git

# Install dependencies
pip install pandas numpy matplotlib scipy scikit-learn ucimlrepo

# Run a notebook
jupyter notebook notebooks/Team_Project.ipynb

# Run a notebook
Requirements
Python 3.8+
pandas
numpy
matplotlib
scipy
scikit-learn
ucimlrepo
Jupyter Notebook

Team Roles
Russell Miller: Exploratory data analysis, repository management, project organization

Alvaro Folgueria: Data loading, cleaning, visualization development, report support

Raul Muollo-Diaz: Model development, evaluation, comparison, QA support

Contact
For questions about this project, contact team members via Slack.

License
This project is for educational purposes as part of the MS-AAI program at the University of San Diego.

Acknowledgments
The team acknowledges the University of San Diego Applied Artificial Intelligence program, especially the course instructors, Leon Shpaner and Dallin Munger as well as the UCI Machine Learning Repository for providing the dataset used in this project.