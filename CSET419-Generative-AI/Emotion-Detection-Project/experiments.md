# Experiments

## Experiment 1: BERT-based Emotion Detection

Model: bert-base-uncased  
Dataset: GoEmotions  
Task: Emotion classification

Training setup:
- Epochs: 1
- Batch size: 8
- Learning rate: 2e-5
- Optimizer: AdamW
- Hardware: Google Colab T4 GPU

Results:

Accuracy: 0.5839  
F1 Score: 0.5598

Observations:
The BERT baseline model is capable of learning emotional patterns from text.
Performance is moderate due to the complexity of the GoEmotions dataset and limited training epochs.
Further improvements could include longer training, hyperparameter tuning, and larger transformer models.
