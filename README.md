# NLP Binary Classification

This repository contains a series of projects focused on **binary text classification** using a Twitter dataset.
The work was developed as part of the *Artificial Intelligence II* course.

The goal is to explore and compare different approaches to text representation and modeling, progressing from classical machine learning methods to modern deep learning architectures.

---

## Overview

The repository is structured into three main approaches, implemented in the following order:

1. **TF-IDF + Logistic Regression**
2. **Word2Vec + Feedforward Neural Network**
3. **Transformers-based Models**

Each approach is implemented as a separate module and includes its own detailed report with explanations, methodology, and results.

---

## Approaches

### 1. TF-IDF + Logistic Regression

* Text is transformed using TF-IDF vectorization
* A Logistic Regression model is trained for classification
* Serves as a strong baseline for comparison

---

### 2. Word2Vec + Feedforward Network

* Word embeddings are generated using Word2Vec
* Sentence representations are constructed
* A Feedforward Neural Network is used for classification

---

### 3. Transformers

* Utilizes transformer-based architectures for text classification
* Captures contextual and semantic information more effectively
* Represents the most advanced approach in this project

---

## Repository Structure

* `Dataset/` — Data used for training and evaluation
* `Tfidf_LogisticRegression/` — Baseline model
* `Word2Vec_FeedForward/` — Embedding-based approach
* `Transformers/` — Transformer-based models

---

## Important Note

These projects were originally developed and executed in a **Kaggle environment**.

To run the notebooks locally, you may need to:

* Adjust dataset file paths accordingly, or
* Modify parts of the code to correctly load local data

Alternatively, you can run the notebooks directly on Kaggle for a smoother experience.

---

## Objective

The main objective of this project is to:

* Compare different text representation techniques
* Evaluate model performance across approaches
* Understand the trade-offs between classical ML and deep learning methods

---

## Notes

Each sub-project includes:

* Detailed implementation
* Explanation of methodology
* Model evaluation and results
* 
---
