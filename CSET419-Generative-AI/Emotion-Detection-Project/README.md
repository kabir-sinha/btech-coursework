![Python](https://img.shields.io/badge/Python-3.10-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-DeepLearning-red)
![Transformers](https://img.shields.io/badge/HuggingFace-Transformers-yellow)
![Task](https://img.shields.io/badge/Task-NLP-green)
![Dataset](https://img.shields.io/badge/Dataset-GoEmotions-orange)

# Emotion Detection in Text using Transformer Models

## Course

CSET419 — Introduction to Generative AI

## Team Members

Kabir Sinha (E23CSEU1343)  
Ayush Srivastava (E23CSEU1344)  
Hamza Usman (E23CSEU1351)

---

## Project Objective

The objective of this project is to explore transformer-based architectures for emotion detection in textual data and evaluate their performance on emotion-labelled datasets using contextual language representations.

---

## Project Overview

Emotion detection in textual data is an important problem in **Natural Language Processing (NLP)**. While traditional sentiment analysis focuses on identifying positive or negative polarity, emotion detection attempts to classify text into finer emotional categories such as happiness, sadness, anger, fear, and surprise.

Accurate emotion recognition from text has applications in several domains including mental health monitoring, human–computer interaction, customer experience analysis, and social media behavior understanding.

Recent advances in **transformer-based language models**, particularly **BERT**, have significantly improved performance across many NLP tasks by capturing contextual relationships between words.

This project investigates the effectiveness of transformer-based approaches for emotion classification in textual data.

---

## Problem Statement

Traditional approaches for emotion detection often rely on bag-of-words representations or classical machine learning models. These approaches typically fail to capture contextual relationships in language, which limits performance when dealing with complex emotional expressions.

Transformer-based architectures overcome these limitations by generating contextual embeddings that capture the meaning of words based on their surrounding context.

The central question addressed in this project is:

**How effectively can transformer-based language models classify emotions in textual data compared to conventional approaches?**

---

## Proposed Approach

The project explores transformer-based models for emotion classification using pretrained contextual embeddings.

The methodology consists of the following steps:

1. Selecting a publicly available emotion-labelled dataset.
2. Preprocessing textual data and converting it into tokenized input sequences.
3. Using transformer encoders to generate contextual word representations.
4. Training a classification layer on top of transformer embeddings.
5. Evaluating model performance using metrics such as **accuracy** and **F1-score**.

The implementation is inspired in part by ideas from the **TACO framework**, which focuses on improved contextual understanding for emotion classification.

---

## Repository Structure

```
Emotion-Detection-Project
│
├── code
│   └── emotion_detection_pipeline.py
│
├── notebooks
│   └── taco_emotion_experiment.ipynb
│
├── dataset.md
├── experiments.md
├── related_work.md
├── requirements.txt
```

Additional documentation is provided in separate markdown files:

- **dataset.md** — dataset description and preprocessing details  
- **experiments.md** — experimental setup and evaluation results  
- **related_work.md** — literature review and research references  

---

## Technologies Used

- Python  
- PyTorch  
- HuggingFace Transformers  
- Scikit-learn  
- Google Colab  

---

## Expected Outcome

The expected outcome of this project is to demonstrate the effectiveness of transformer-based architectures for emotion detection tasks and analyze their performance using standard evaluation metrics.

The study also highlights the advantages of contextual embeddings in understanding emotional expressions within natural language.

---

## References

Devlin, J., Chang, M. W., Lee, K., & Toutanova, K. (2019).  
**BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding.**

Demszky, D., Movshovitz-Attias, D., Ko, J., Cowen, A., Nemade, G., & Ravi, S. (2020).  
**GoEmotions: A Dataset of Fine-Grained Emotions.**

TACO Framework Implementation  
https://github.com/Alcyoneus87/TACO
