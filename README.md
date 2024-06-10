# Identifying Entities in Healthcare Data

## Table of Contents:
* [Introduction](#introduction)
* [Problem Statement](#problem-statement)
* [Objectives](#objectives)
* [Datasets Description](#datasets-description)
* [Major Tasks](#major-tasks)
* [Analysis Approach](#analysis-approach) 
* [Technologies Used](#technologies-used)
* [References](#references)
* [Contact Information](#contact-information)

## Introduction:
<div align="justify">This notebook contains a notebook of building a custom Named Entity Recognition (NER) system for extracting diseases and their probable treatments from medical text data. A health tech company called "BeHealthy" wants a predictive model that can correctly detect diseases and treatments mentioned in patient interactions with doctors or during the process of ordering medicines online. The task involves extracting disease names and their corresponding treatments from medical text data using a Conditional Random Field (CRF) model.</div>

## Problem Statement: 
<div align="justify">Understanding medical text data can be difficult for individuals without a medical background. Extracting valuable facts or information, such as diseases and treatments, from such datasets is important for various applications. In this project, we aim to create a custom Named Entity Recognition (NER) system to identify diseases and their probable treatments from provided medical text data.</div>

## Objectives: 
<div align="justify">The main goal is to develop a custom NER system capable of identifying diseases and their probable treatments from provided medical text data.</div>

## Datasets Description:  

<div align="justify">We are provided with four datasets:<br>

1. Train Sentence Dataset: It contains sentences used for training the NER model.<br>

2. Train Label Dataset: It contains labels corresponding to the words in the training set, indicating whether each word represents 'Other' (O), 'Disease' (D), or 'Treatment' (T).<br>

3. Test Sentence Dataset: It contains sentences for evaluating the trained model.<br>

4. Test Label Dataset: It contains labels corresponding to the test sentences.<br>
</div>


## Major Tasks:

There are eight major tasks that we need to perform to complete the assignment. They are as follows:<br>

1. Data preprocessing<br>

2. Concept identification<br>

3. Defining the features for CRF<br>

4. Getting the features words and sentences<br>

5. Defining input and target variables<br>

6. Building the model<br>

7. Evaluating the model<br>

8. Identifying the diseases and predicted treatment using a custom NER

## Analysis Approach:   
<div align="justify">To tackle this problem effectively, I have established a structured data analysis approach.<br>

- Data Preparation:<br> In this step we combine individual words into sentences based on the provided dataset structure for both training and testing data.

- Feature Definition:<br> It involves defining the features to build the Conditional Random Fields (CRF) model. These features will be applied to each sentence in both the training and test datasets.

- Feature Extraction:<br> We compute feature values for each sentence in the datasets.

- Model Building:<br>We define the target variable and build the CRF model using the extracted features.

- Evaluation: <br> It involves evaluating the performance of the model using the test dataset.

- Dictionary Creation: <br> It involves creating a dictionary mapping diseases to their respective treatments based on the model predictions.</div>

## Technologies Used:
- Python, version 3 
- NumPy for numerical computations
- Matplotlib and seaborn for data visualization
- Pandas for data manipulation
- Statsmodels for statistical modeling
- Sklearn for machine learning tasks
- NLTK (Natural Language Toolkit) and spaCy
- Jupyter Notebook for interactive analysis

## References:
- Python documentations
- Exploratory Data Analysis
- Stack Overflow
- NLTK (Natural Language Toolkit)
- spaCy 
- Medium NLP Articles 
- Kaggle


## Contact Information:
Created by https://github.com/Erkhanal - feel free to contact!
