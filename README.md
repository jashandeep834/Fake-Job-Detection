# Fake Job Detection using Machine Learning

This project builds a machine learning model to detect fraudulent job postings using Natural Language Processing (NLP) techniques.  
The model analyzes job descriptions and other features to classify whether a job posting is real or fake.

The goal of this project is to help job seekers avoid fraudulent job listings and improve trust in online job platforms.


## Project Overview

Online job platforms often contain fraudulent job postings that can mislead job seekers.  
This project uses machine learning and text processing techniques to automatically identify fake job postings.

The system processes job listing text data, converts it into numerical features using TF-IDF vectorization, and trains classification models to detect fake postings.


## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Natural Language Processing (NLP)
- TF-IDF Vectorization
- Jupyter Notebook

## Machine Learning Workflow

The project follows these steps:

1. Data Collection  
   Load the fake job postings dataset.

2. Data Cleaning  
   Handle missing values and prepare text data.

3. Text Preprocessing  
   Combine title and description fields and clean text.

4. Feature Extraction  
   Convert text data into numerical vectors using TF-IDF.

5. Model Training  
   Train classification algorithms to detect fake job postings.

6. Model Evaluation  
   Evaluate model performance using accuracy and other metrics.


## Dataset

The dataset contains job postings with information such as:

- Job Title
- Job Description
- Company Profile
- Location
- Required Experience
- Fraudulent Label (Real or Fake)

The target variable identifies whether a job posting is fraudulent.

