# Species Distribution Modelling

A machine learning project exploring species distribution using environmental and spatial data.

This repository contains the work I contributed to as part of a **UNSW group project**, with a focus on exploratory data analysis, data preprocessing, and Logistic Regression modelling.

## Project Overview

The aim of the project was to investigate how environmental and spatial variables can be used to model species presence and distribution.

The broader team project explored multiple machine learning approaches. This repository focuses specifically on the work I personally contributed.

## My Contribution

My work focused on:

- Exploratory Data Analysis (EDA)
- Data preprocessing and preparation
- Investigating feature distributions and relationships
- Building a baseline Logistic Regression model
- Developing a Regularised Logistic Regression model
- Handling class imbalance
- Model tuning
- Cross-validation
- Evaluating and interpreting model performance

## Repository Structure

```text
species-distribution-modelling/
│
├── notebooks/
│   ├── 01_exploratory_data_analysis.ipynb
│   ├── 02_logistic_regression_baseline.ipynb
│   └── 03_regularised_logistic_regression.ipynb
│
├── images/
│   ├── eda-overview.png
│   ├── class-distribution.png
│   ├── logistic-regression-results.png
│   └── regularised-model-results.png
│
├── data/
│   └── README.md
│
├── README.md
├── requirements.txt
└── .gitignore
```
# Exploratory Data Analysis
The exploratory analysis focused on understanding the structure of the dataset before modelling.
This included:
- Examining feature distributions
- Identifying missing or unusual values
- Exploring species presence and absence patterns
- Investigating class imbalance
- Analysing relationships between predictors
- Preparing the data for modelling
# Baseline Logistic Regression
A baseline Logistic Regression model was developed as an interpretable starting point.
The baseline helped evaluate:
- How well a simple statistical model could represent the data
- The impact of class imbalance
- Model behaviour before regularisation
- Areas where performance could be improved
# Regularised Logistic Regression
The baseline model was extended using regularisation.
Regularisation was used to:
- Reduce overfitting
- Improve generalisation
- Control model complexity
- Handle less informative or correlated predictors
Cross-validation and model tuning were used to evaluate the regularised model more reliably.
# Model Evaluation
The models were evaluated using classification metrics and validation techniques.
Depending on the notebook outputs, these may include:
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix
- Cross-validation performance
Only keep the metrics above that are actually calculated in the notebooks.
# Team Project Context
This work was originally completed as part of a UNSW group academic project.
The complete team project explored additional modelling approaches, but this repository only contains the work associated with my contribution.
Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook
- Logistic Regression
- Cross-validation
- Git
# Dataset
The dataset is not stored directly in this repository.
Add the original dataset source here: https://www.kaggle.com/competitions/predicting-small-reptile-species-distributions-in-nsw/overview
# Running the Project
Clone the repository:
git clone https://github.com/PranavNG/species-distribution-model.git

cd species-distribution-modelling

# Create a virtual environment:
python -m venv .venv

# Activate it.
macOS / Linux
source .venv/bin/activate

# Windows
.venv\Scripts\activate

# Install dependencies:
pip install -r requirements.txt

Then open the notebooks in order:
01_exploratory_data_analysis.ipynb

02_logistic_regression_baseline.ipynb

03_regularised_logistic_regression.ipynb

# Key Takeaways
This project gave me experience in moving through the modelling workflow from exploratory analysis and preprocessing to model development, tuning and evaluation.
It also reinforced the importance of:
- Establishing a baseline before moving to more complex models
- Accounting for class imbalance
- Using cross-validation for more reliable evaluation
- Balancing predictive performance with interpretability
- Understanding the data before selecting a modelling approach
# Author
Pranav Ghatigar
- GitHub: PranavNG
- LinkedIn: www.linkedin.com/in/pranav-ghatigar
