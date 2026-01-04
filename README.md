# Course Repository

This repository contains notebooks and resources for the Data Science course. It covers Python basics, libraries like Numpy and Pandas, Data Visualization, Machine Learning with Scikit-learn, Text Analysis, and Explainable AI.

## Index

### 1. Python
- [Python Essentials](1-Python/1a_PythonEssentials.ipynb): **Python Informal Introduction**. Covers fundamentals, interpreted language, indentation, object-oriented nature, and using Python as a calculator.
- **Exercises**:
    - [Python Basic](1-Python/esercizi/1_Esercizi_PythonBasic.ipynb)
    - [Python Essential](1-Python/esercizi/1_Esercizi_PythonEssential.ipynb)

### 2. Numpy
- [Numpy Basics](2-Numpy/2a_Numpy.ipynb): **Numpy**. Covers the `ndarray` object, creating arrays, shape, dtype, and efficient data storage.
- **Exercises**:
    - [Numpy Exercises](2-Numpy/esercizi/2_Esercizi_Numpy.ipynb)
    - [Classroom Exercise](2-Numpy/esercizi/Esercizio%20in%20aula.ipynb)

### 3. Pandas
- [Pandas Basic](3-Pandas/3a_Pandas_basic.ipynb): **Getting started with Pandas**. Covers Series and Dataframe data structures.
- [Pandas Managing Data](3-Pandas/3b_Pandas_ManagingData.ipynb): **Data Loading, Storage**. Covers reading and writing data in text format (CSV).
- **Exercises**:
    - [Pandas Basic Exercises](3-Pandas/esercizi/3_Esercizi_Pandas_basic_student.ipynb)
    - [Classroom Exercise](3-Pandas/esercizi/Esercizio%20in%20aula.ipynb)

### 4. Pandas Advanced
- [Using Pandas Part I](4-Pandas%20advanced/4a_Using_Pandas%20Part%20I.ipynb): **Handling Missing Data**. Covers NaN, filtering out missing data (`dropna`).
- [Using Pandas Part II](4-Pandas%20advanced/4a_Using_Pandas%20Part%20II.ipynb): **Data Wrangling**. Covers Hierarchical Indexing, cleaning, transforming, merging, and reshaping.
- **Exercises**:
    - [Using Pandas Part I Exercises](4-Pandas%20advanced/esercizi/4_Esercizi_Using_Pandas_student%20Part%20I.ipynb)
    - [Using Pandas Part II Exercises](4-Pandas%20advanced/esercizi/4_Esercizi_Using_Pandas_student%20Part%20II.ipynb)
    - [Classroom Exercise](4-Pandas%20advanced/esercizi/Esercizio%20in%20aula.ipynb)

### 5. Data Visualization
- [Data Visualization](5-Data%20Visualization/5_DataVisualization.ipynb): **Matplotlib**. Covers General Concepts (Figure, Axes, Axis, Artist) and the Pyplot interface.
- **Exercises**:
    - [Data Visualization Exercise](5-Data%20Visualization/esercizi/5_DataVisualization_ExerciseText.ipynb)
    - [Classroom Exercise](5-Data%20Visualization/esercizi/Esercizio%20in%20aula.ipynb)

### 6. Sklearn Basics
- [Sklearn Basics](6-Sklearn%20basics/6a_Sklearn.ipynb): **Scikit-Learn**. Covers Data Representation (Features matrix, Target array) and the Estimator API (`fit`, `predict`).
- [Preprocessing](6-Sklearn%20basics/6b_Preprocessing.ipynb): **Preprocessing data**. Covers Standardization (mean removal, variance scaling) and `StandardScaler`.
- **Exercises**:
    - [Bank Exercise - Transformation and Prediction](6-Sklearn%20basics/esercizi/Esercizio%20banca%20-%20Trasformazione%20e%20predizione.ipynb)
    - [Iris Exercise](6-Sklearn%20basics/esercizi/Esercizio%20iris.ipynb)

### 7. Sklearn Advanced
- [Model Evaluation and Selection](7-Sklearn%20advanced/7a_Model_Evaluation_And_Selection.ipynb): **Model Evaluation**. Covers Classification metrics (Accuracy, Precision, Recall, F1) and Confusion Matrix.
- [Pipeline](7-Sklearn%20advanced/7b_Pipeline.ipynb): **Pipelines**. Covers sequential application of transforms and a final estimator.
- [Text Preprocessing TfIdf](7-Sklearn%20advanced/7c_Text_Preprocessing_TfIdf.ipynb): **Text Preprocessing**. Covers loading datasets, removing line breaks, and length analysis (Spam detection context).
- **Exercises**:
    - [Classification Exercise](7-Sklearn%20advanced/esercizi/7_Classification_Exercise.ipynb)
    - [Cross Validation Exercise](7-Sklearn%20advanced/esercizi/7_CrossValidation_Exercise.ipynb)
    - [Grid Search Exercise](7-Sklearn%20advanced/esercizi/7_GridSearch_Exercise.ipynb)
    - [Regression Exercise](7-Sklearn%20advanced/esercizi/7_Regression_Exercise.ipynb)
    - [Car Price](7-Sklearn%20advanced/esercizi/Car%20price.ipynb)
    - [Drug Review - Text Preprocessing](7-Sklearn%20advanced/esercizi/Drug%20Review%20-%20Text%20preprocessing.ipynb)
    - [Heart Failure Prediction](7-Sklearn%20advanced/esercizi/Heart%20Failure%20Prediction.ipynb)

### 8. Simulations and Practice (Esercitazioni)
- **Fairness**: [Hiring Decisions](8-Esercitazioni/Fairness/Hiring_Decisions.ipynb)
- **Mobile Price Classification**: [Pipeline](8-Esercitazioni/Mobile%20price%20classification/pipeline.ipynb)
- **Simulation 20250618**: [Part 1](8-Esercitazioni/Simulazione%2020250618/simulazione%2018-06-25%20-%20Parte%201.ipynb)

### Text Analysis
- **Retrieval & Fact Checking**:
    - [Simple Finetuning Sentence Pair](textAnalysis/text_analysis_retrieval_fact_checking/5_simple_finetuning_sentencepair.ipynb)
    - [Fact Checking](textAnalysis/text_analysis_retrieval_fact_checking/FactChecking.ipynb): **Fact Checking**. Covers automated fact-checking tasks.
- **Transformers**:
    - [Sentence Embeddings](textAnalysis/text_analysis_transformers/notebooks/1_sentence_embeddings.ipynb): **Sentence Embeddings**. Covers BERT, tokenization, and extracting sentence embeddings.
    - [Text Classification](textAnalysis/text_analysis_transformers/notebooks/2_text_classification.ipynb)
    - [Text Clustering & Topic Modeling](textAnalysis/text_analysis_transformers/notebooks/3_text_clustering_topic_modeling.ipynb)
    - [BERT Applications](textAnalysis/text_analysis_transformers/notebooks/4_bert_applications.ipynb)

### XAI (Explainable AI)
- [LIME Iris](XAI/lime_iris.ipynb): **LIME with tabular data**. Covers using LIME to explain model predictions on the Iris dataset.
- [LIME Spam](XAI/lime_spam.ipynb)
