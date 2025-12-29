# Intent Classification using Machine Learning (NLP)

This repository implements a **machine learning–based intent classification system** using classical Natural Language Processing techniques.  
The project is designed as a **clean, minimal, and explainable baseline** for dialogue systems, chatbots, and human–robot interaction pipelines.

The implementation is provided in a **Jupyter Notebook** for transparency and reproducibility.

---

## Problem Statement

Given a user utterance in natural language, predict the **intent** behind the utterance.

This is formulated as a **supervised multi-class text classification problem**.

---

## Dataset

The dataset consists of short text utterances labeled with intent classes.

Example:

| Text              | Intent     |
|-------------------|------------|
| hello there       | greeting   |
| can you help me   | help       |
| stop talking      | annoyance  |

The dataset is intentionally lightweight to emphasize the **end-to-end ML pipeline** rather than dataset scale.

---

## Methodology

### Text Representation
- TF-IDF (Term Frequency–Inverse Document Frequency)

### Model
- Logistic Regression

The model is implemented using a **Scikit-learn Pipeline**, combining feature extraction and classification into a single workflow.

---

## Pipeline Overview

