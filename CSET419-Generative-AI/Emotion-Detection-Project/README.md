# Emotion Detection in Text using Transformer Models

## Course
CSET419 — Introduction to Generative AI

## Team Members
Kabir Sinha (E23CSEU1343)  
Ayush Srivastava (E23CSEU1344)  
Hamza Usman (E23CSEU1351)

---

# Project Overview

Emotion detection in textual data is an important problem in Natural Language Processing (NLP). While traditional sentiment analysis focuses on identifying positive or negative polarity, emotion detection attempts to classify text into finer emotional categories such as happiness, sadness, anger, fear, and surprise.

Accurate emotion recognition from text has applications in several domains including mental health monitoring, human–computer interaction, customer experience analysis, and social media behavior understanding.

This project explores the use of transformer-based contextual language models for detecting emotions from textual data. Transformer architectures such as BERT have significantly improved performance across NLP tasks by capturing contextual relationships between words.

The objective of this project is to evaluate transformer-based approaches for emotion classification and analyze their effectiveness compared to conventional text classification techniques.

---

# Problem Statement

Most traditional approaches for emotion detection rely on bag-of-words representations or classical machine learning models. These approaches fail to capture contextual relationships in language, leading to limited performance when handling complex emotional expressions.

With the emergence of transformer-based models, contextual embeddings can better represent linguistic nuances in text.

The problem addressed in this project is:

How effectively can transformer-based language models classify emotions in textual data compared to conventional approaches?

---

# Proposed Approach

The project investigates transformer-based models for emotion classification using pre-trained contextual embeddings.

The methodology consists of the following steps:

1. Selecting publicly available emotion-labelled datasets.
2. Preprocessing textual data and converting it into tokenized input sequences.
3. Utilizing transformer-based encoders for generating contextual representations.
4. Training a classification layer on top of transformer embeddings.
5. Evaluating model performance using standard metrics such as accuracy and F1-score.

The project also experiments with an implementation inspired by the **TACO framework**, which focuses on improved contextual understanding for emotion classification.

---

# Repository Structure

Emotion-Detection-Project/

README.md — Project overview  
related_work.md — Literature review and research papers  
dataset.md — Dataset description and preprocessing  
experiments.md — Experimental setup and results  

notebooks/  
taco_emotion_experiment.ipynb  

---

# Technologies Used

Python  
PyTorch  
HuggingFace Transformers  
Scikit-learn  
Google Colab

---

# Expected Outcome

The expected outcome of this project is to demonstrate the effectiveness of transformer-based architectures for emotion detection tasks and analyze their performance across standard evaluation metrics.

The study also aims to highlight the advantages of contextual embeddings in understanding emotional expressions within natural language.
