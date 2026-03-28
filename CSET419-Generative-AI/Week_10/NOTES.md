# Week 10 Notes — Sequential Data Generation with LSTM and Transformer

Sequential Data:
- Data where order is important
- Examples: text, sentences, language modeling

Tokenization:
- Converting words into numerical form
- Each word mapped to a unique index

Sequence Preparation:
- Sliding window approach used
- Input sequence → Next word prediction

LSTM:
- Type of Recurrent Neural Network
- Maintains long-term dependencies
- Uses hidden states and memory cells
- Processes data sequentially

Transformer:
- Uses self-attention mechanism
- Processes sequences in parallel
- Captures global relationships between words

Positional Encoding:
- Adds positional information to embeddings
- Helps Transformer understand word order
- Uses sine and cosine functions

Text Generation:
- Model predicts next word iteratively
- Seed input used to start generation
- Greedy decoding (argmax) used

Observations:
- LSTM captures sequence flow effectively
- Transformer generates context-aware outputs
- Small dataset leads to repetition in output

Key Insight:
LSTM models sequential dependencies, while Transformers use attention and positional encoding to capture relationships across the entire sequence.
