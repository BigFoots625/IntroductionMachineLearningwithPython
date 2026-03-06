# Introduction to Machine Learning with Python 🧠🐍

This repository contains my comprehensive study notes, theoretical explanations, and code reproductions based on the book *"Introduction to Machine Learning with Python: A Guide for Data Scientists"* by Andreas C. Müller and Sarah Guido.

## Project Overview
The goal of this project is to build a rigorous, practical foundation in machine learning. Moving beyond simply executing code, this repository deeply explores the mathematics and theories behind core algorithms, data preprocessing, feature engineering, and model evaluation. 

Each chapter is contained within its own Jupyter Notebook, featuring:
- Reproductions of the book's core Python implementations.
- Expanded theoretical breakdowns of how and why the algorithms work.
- Practical chapter summaries and key takeaways.

## Repository Contents

* **[Chapter 1: Introduction](./Chapter_1_Introduction)** * Understanding the ML landscape, data representation, and building a foundational k-Nearest Neighbors (k-NN) model.
* **[Chapter 2: Supervised Learning](./Chapter_2_Supervised_Learning)**
  * Linear models (Ridge, Lasso, Logistic), Naive Bayes, Decision Trees, Ensembles (Random Forests, GBRT), Kernelized SVMs, and Neural Networks (MLPs).
* **[Chapter 3: Unsupervised Learning and Preprocessing](./Chapter_3_Unsupervised_Learning)**
  * Data scaling methodologies, dimensionality reduction (PCA, NMF, t-SNE), and clustering algorithms (k-Means, Agglomerative, DBSCAN).
* **[Chapter 4: Representing Data and Engineering Features](./Chapter_4_Representing_Data)**
  * One-hot encoding, binning, polynomial features, and automatic feature selection (Univariate, Model-Based, RFE) to optimize data for linear models and trees.
* **[Chapter 5: Model Evaluation and Improvement](./Chapter_5_Model_Evaluation)**
  * Cross-validation strategies, exhaustive Grid Search for hyperparameter tuning, and advanced evaluation metrics (Precision, Recall, F1-Score, ROC/AUC) for imbalanced datasets.
* **[Chapter 6: Algorithm Chains and Pipelines](./Chapter_6_Algorithm_Chains)**
  * Preventing data leakage and streamlining workflows by combining preprocessing and modeling steps into cohesive `scikit-learn` Pipelines.
* **[Chapter 7: Working with Text Data](./Chapter_7_Text_Data)**
  * Natural Language Processing (NLP) techniques including Bag-of-Words, TF-IDF rescaling, n-grams, lemmatization (via spaCy), and Topic Modeling (LDA).
* **[Chapter 8: Wrapping Up](./Chapter_8_Wrapping_Up)**
  * Approaching ML from a software engineering perspective: problem definition, productionization, building custom `scikit-learn` estimators, and A/B testing.

## Tech Stack
- **Language:** Python 3.x
- **Core ML Library:** `scikit-learn`
- **Data Manipulation:** `NumPy`, `Pandas`
- **Visualization:** `Matplotlib`, `mglearn`
- **NLP:** `spaCy`
- **Environment:** Jupyter Notebook / Google Colab

## About 
I am currently a 6th-semester Computer Engineering student at Telkom University, building a robust technical foundation for a future career as a data analyst and data engineer. This repository serves as a living document of my journey into the mechanics of machine learning and data engineering pipelines.
