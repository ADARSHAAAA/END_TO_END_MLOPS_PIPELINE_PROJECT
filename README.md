# END_TO_END_MLOPS_PIPELINE_PROJECT

Project Overview::

Data Collection & Ingestion: 
      Collected and ingested a spam dataset, including error handling to manage any data loading issues.
Data Preprocessing & Feature Engineering: 
     Cleaned the text data and extracted useful features for modeling.
Model Building:
     Trained a machine learning classification model (e.g., Naive Bayes) on the processed data to detect spam.
Model Evaluation:
      Evaluated the model using performance metrics such as accuracy, precision, and recall.
Experiment Tracking:
      Used DVC (Data Version Control) and DVCLive to create a reproducible pipeline, version data, and log parameters/metrics.
Deployment: 
     Saved the trained model as a .pkl file and deployed the project on AWS for cloud-based access


Languages & Environments:
     python 3.13.5 (managed via Conda)
     Jupyter Notebook (IPython kernel)
Data Handling & NLP:
  Pandas, NumPy
  NLTK (tokenization, stopwords) or spaCy
Feature Engineering & Preprocessing:
    Scikit‑learn (TF‑IDF, vectorizers)
Modeling & Evaluation:
    Scikit‑learn classifiers (e.g., Naive Bayes, Logistic Regression)
Metrics: 
   accuracy, precision, recall
Pipeline & Experiment Tracking:
    DVC (dvc.yaml, dvc repro, dvc dag)
    DVCLive (for logging params & metrics)
    YAML (params.yaml)
Version Control & CI:
     Git & GitHub
Deployment & Cloud:
    Model serialization: pickle (.pkl)
    AWS (e.g., S3 for storage, EC2/Elastic Beanstalk or Lambda for hosting)
Exception Handling & Logging:
  Python’s try/except blocks
  Standard logging module
