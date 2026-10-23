# Loan Approval Prediction Using Machine Learning

## Project Overview

This project focuses on building a Loan Approval Prediction System using
Machine Learning. The objective is to analyze applicant information,
clean and preprocess the dataset, perform Exploratory Data Analysis
(EDA), and train classification models to predict whether a loan
application is likely to be approved.

The project demonstrates a complete machine learning pipeline, from data
preprocessing to model evaluation.

------------------------------------------------------------------------

## Objectives

-   Clean and preprocess a real-world loan dataset.
-   Perform Exploratory Data Analysis (EDA).
-   Handle missing values and inconsistent data.
-   Visualize relationships between different features.
-   Train and evaluate Machine Learning classification models.
-   Predict loan approval status based on applicant details.

------------------------------------------------------------------------

## Dataset

**Dataset:** `LoanUncleanedDataset.csv`

The dataset contains loan applicant information such as:

-   Age
-   Monthly Income
-   Co-applicant Income
-   Loan Amount
-   Loan Duration
-   CIBIL Score
-   Employment Years
-   Existing Loans
-   Residential Area
-   Loan Status

------------------------------------------------------------------------

## Technologies Used

-   Python
-   Jupyter Notebook
-   NumPy
-   Pandas
-   Matplotlib
-   Seaborn
-   Scikit-learn

------------------------------------------------------------------------

## Exploratory Data Analysis (EDA)

The notebook includes:

-   Dataset overview
-   Shape of dataset
-   Data types
-   Statistical summary
-   Missing value analysis
-   Correlation analysis
-   Covariance analysis
-   Data visualization

------------------------------------------------------------------------

## Data Preprocessing

The preprocessing pipeline includes:

-   Handling missing values
-   Data cleaning
-   Removing invalid entries
-   Feature engineering
-   Encoding categorical variables
-   Feature scaling

------------------------------------------------------------------------

## Machine Learning Workflow

1.  Import Libraries
2.  Load Dataset
3.  Data Cleaning
4.  Exploratory Data Analysis
5.  Feature Engineering
6.  Data Preprocessing
7.  Model Training
8.  Model Evaluation
9.  Loan Approval Prediction

------------------------------------------------------------------------

## Evaluation Metrics

The machine learning models are evaluated using:

-   Accuracy
-   Precision
-   Recall
-   F1-Score
-   Confusion Matrix

------------------------------------------------------------------------

## Project Structure

``` text
Loan-Approval-Prediction/
│
├── LoanApplicationSystem.ipynb
├── LoanUncleanedDataset.csv
├── README.md

```

------------------------------------------------------------------------

## How to Run

### 1. Clone the Repository

``` bash
git clone https://github.com/your-username/Loan-Approval-Prediction.git
```

### 2. Navigate to the Project Folder

``` bash
cd Loan-Approval-Prediction
```

### 3. Install Required Libraries

``` bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

### 4. Launch Jupyter Notebook

``` bash
jupyter notebook
```

Open `LoanApplicationSystem.ipynb` and run the notebook cells
sequentially.

------------------------------------------------------------------------

## Features

-   Complete data preprocessing pipeline
-   Exploratory Data Analysis
-   Correlation and covariance visualization
-   Missing value handling
-   Machine learning model training
-   Loan approval prediction

------------------------------------------------------------------------

## Future Improvements

-   Deploy using Flask or Django
-   Build a React frontend
-   Add multiple ML models for comparison
-   Hyperparameter tuning
-   Model deployment using Docker
-   Cloud deployment (AWS, Azure, or GCP)

------------------------------------------------------------------------