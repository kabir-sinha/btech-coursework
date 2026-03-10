# Dataset Description

## Overview

Emotion detection requires datasets that contain text samples annotated with emotional categories. In this project, publicly available emotion-labelled datasets are used to train and evaluate transformer-based models for emotion classification.

The primary dataset used in this study is the **GoEmotions dataset**, which is widely used in emotion classification research.

---

# GoEmotions Dataset

The GoEmotions dataset was introduced by Demszky et al. (2020) and contains a large collection of Reddit comments annotated with emotional labels.

### Key Characteristics

Number of samples: ~58,000 Reddit comments  
Number of emotion categories: 27  
Annotation type: Human annotated  
Language: English  

The dataset contains both single-label and multi-label emotion annotations, allowing researchers to study complex emotional expressions.

### Example Emotion Categories

Some of the emotion labels included in the dataset are:

- Joy  
- Sadness  
- Anger  
- Fear  
- Surprise  
- Disgust  
- Gratitude  
- Admiration  
- Excitement  

These fine-grained labels make the dataset suitable for training deep learning models that aim to capture subtle emotional differences in text.

---

# Data Preprocessing

Before training the model, the dataset undergoes several preprocessing steps to ensure compatibility with transformer architectures.

### Preprocessing Steps

1. Removal of empty or invalid samples.
2. Text normalization.
3. Tokenization using a transformer tokenizer.
4. Conversion of text inputs into token IDs.
5. Creation of attention masks for transformer inputs.

Tokenization is performed using the tokenizer corresponding to the selected transformer model.

---

# Data Splitting

The dataset is divided into three subsets:

Training set — used to train the model  
Validation set — used for hyperparameter tuning  
Test set — used to evaluate final performance

This split ensures that model evaluation is performed on unseen data.

---

# Dataset Usage in This Project

The dataset is used to train a transformer-based model for emotion classification. Each text sample is mapped to its corresponding emotion label and used as input for the classification model.

The model learns contextual representations of emotional language through transformer-based embeddings.

---

# References

Demszky, D., Movshovitz-Attias, D., Ko, J., Cowen, A., Nemade, G., & Ravi, S. (2020).  
**GoEmotions: A Dataset of Fine-Grained Emotions.**  
Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics (ACL).
