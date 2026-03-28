# Week 09 — Sequence Generation using LSTM and Transformer

## Objective
To understand and implement generative models for sequential data using LSTM and Transformer architectures.

## Approach
- Preprocessed text dataset into sequences
- Converted words into numerical representations
- Created input-output sequence pairs
- Implemented LSTM-based model for sequence prediction
- Implemented a simple Transformer model using attention mechanism
- Trained both models on the dataset
- Generated new sequences using seed inputs

## Model Details
### LSTM Model
- Embedding layer
- LSTM layer
- Fully connected output layer

### Transformer Model
- Embedding layer
- Multi-head attention
- Linear output layer

## Training Details
- Loss Function: CrossEntropyLoss
- Optimizer: Adam
- Epochs: 200

## Outputs
- Generated sequences using LSTM
- Generated sequences using Transformer

## Files

### Dataset
- No external dataset (inline text used)

### Notebook
- notebook/CSET419_GenAI_Lab9.ipynb

### Report
- report/E23CSEU1343-Kabir-CSET419-Lab9.pdf

## Conclusion
Both LSTM and Transformer models successfully learned sequence patterns from the dataset and generated meaningful text sequences. LSTM captures sequential dependencies through hidden states, while Transformer uses attention mechanisms for sequence modeling.
