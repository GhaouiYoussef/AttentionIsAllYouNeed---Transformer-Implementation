# Transformer Implementation - Attention Is All You Need

This repository contains a documented implementation of the **Attention Is All You Need** paper, which introduced the Transformer architecture. The Transformer model has become foundational in natural language processing (NLP) and beyond, providing the basis for models like BERT, GPT, and T5.
![plot](/transformer architecture.png)


## Repository Structure

- **`README.md`**: This file, providing an overview of the repository.
- **`Building a Transformer with Pytorch.ipynb`**: A Jupyter notebook implementing the Transformer model using PyTorch. This notebook walks through the key steps in building a Transformer and includes code and explanations.
- **`attention_is_all_you_need.pdf`**: A PDF version of the original **Attention Is All You Need** paper for reference.
- **`.gitignore`**: Standard Git ignore file to exclude unnecessary files from version control.

## Overview of the Transformer

The Transformer architecture introduced in the **Attention Is All You Need** paper revolutionized NLP by removing the recurrent structure used in models like RNNs and LSTMs, relying instead on self-attention mechanisms. Key components include:

- **Self-Attention**: A mechanism that allows the model to weigh the importance of different tokens in a sequence, regardless of their position.
- **Positional Encoding**: Since the Transformer lacks inherent sequence processing like RNNs, positional encodings are added to the input embeddings to retain information about the order of tokens.
- **Multi-Head Attention**: This allows the model to focus on different parts of the sequence simultaneously, enhancing its ability to capture complex patterns.
- **Feedforward Neural Networks**: These are used after the attention layers to process the sequence further.
  
## How to Use

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/GhaouiYoussef/Transformer-Implementation.git
   cd Transformer-Implementation

