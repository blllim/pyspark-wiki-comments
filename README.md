# Detecting offensive language in Wikipedia comments

## Contents:

1. Exploratory Data Analysis
2. Data Preparation
3. Analysis
    - Model fitting with Logistic Regression using original dataset (with Bigrams)
    - Model fitting using resampled datasets
        - Logistic Regression with Bigrams
        - Logistic Regression without Bigrams
        - Linear SVC with Bigrams
        - Linear SVC without Bigrams
        - Random Forest with Bigrams
        - Random Forest without Bigrams<br>
    - Model selection with parameter grid and cross-validation
        - Logistic Regression (without Bigrams)
        - Random Forest (without Bigrams)
4. Results

## Instructions
- Install the necessary packages - matplotlib, wordcloud and nltk
- Install Spark NLP (https://nlp.johnsnowlabs.com/docs/en/install#python) using 
    - pip install spark-nlp==3.4.1
    <br>or
    - conda install -c johnsnowlabs spark-nlp

## Comments
- Some cells may take more than a few minutes to run
