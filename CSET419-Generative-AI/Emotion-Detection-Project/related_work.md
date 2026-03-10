# Related Work

Emotion detection in text has been an active area of research within Natural Language Processing. Early approaches relied primarily on lexicon-based methods and traditional machine learning techniques. However, recent advancements in deep learning and transformer architectures have significantly improved performance in emotion classification tasks.

## 1. Transformer-Based Emotion Recognition

Transformer-based models such as BERT have revolutionized NLP by capturing contextual word relationships using self-attention mechanisms.

Devlin et al. (2019) introduced **BERT (Bidirectional Encoder Representations from Transformers)**, which enables deep bidirectional understanding of textual context. BERT-based architectures have been widely adopted for various NLP tasks including sentiment analysis and emotion detection.

These contextual embeddings allow models to better understand subtle emotional expressions compared to traditional bag-of-words approaches.

## 2. Emotion Classification using Pre-trained Language Models

Recent research has focused on fine-tuning pre-trained language models for emotion detection tasks. By leveraging contextual embeddings learned from large corpora, models can generalize better to complex emotional expressions.

Studies have demonstrated that transformer-based approaches significantly outperform traditional machine learning methods such as Support Vector Machines and Naive Bayes classifiers when applied to emotion-labelled datasets.

## 3. GoEmotions Dataset

Demszky et al. (2020) introduced the **GoEmotions dataset**, a large-scale dataset of human-annotated Reddit comments labelled with multiple emotional categories. The dataset contains over 58,000 comments annotated across 27 emotion categories.

GoEmotions has become a widely used benchmark for evaluating emotion classification models due to its diversity and fine-grained emotion labels.

## 4. TACO Framework

The **TACO (Transformer-based Adaptive Context Optimization)** framework proposes improvements in contextual understanding for emotion detection tasks. The framework leverages transformer architectures and enhanced contextual representations to improve classification performance.

The implementation used in this project is based on the publicly available repository:

https://github.com/Alcyoneus87/TACO

The framework demonstrates how contextual modeling techniques can improve emotion recognition performance across datasets.

## Summary

Existing research demonstrates that transformer-based models significantly improve emotion detection performance by capturing contextual relationships in language. This project builds upon these developments by exploring transformer-based architectures for emotion classification and evaluating their effectiveness on emotion-labelled datasets.
