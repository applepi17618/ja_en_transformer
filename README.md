# Japanese-English Transformer Model 🗻
A from-scratch implementation of the Transformer architecture for Japanese-English machine translation, implemented following the 2017 Google paper to study the model's mechanics and address Japanese NLP nuances.

## 🤖 Quick Overview
- Model: Transformer with the paper parameters (6 layers, 8 attention heads, 512-dim embeddings)
- Data: 68,000 Japanese-English sentence pairs from the Tatoeba Project database
- Training: Built from scratch using PyTorch
- Focus: Architectural transparency & Japanese linguistic analysis

## 🤖 Stack

- **Python 3.12** 🐍
- **SentencePiece** 📃
- **NLTK** 🖋️

## 🤖 Performance Metrics

| Metric | Value |
|:---------|:---------|
| **Training Loss**  | 0.1459   |
| **Validation Loss**  | 2.8688  | 
| **Perplexity**   | 1.1571   | 
| **BLEU Score**             |      0.6270  |

## 🤖 Key Features

- **From-Scratch Implementation**: A complete Transformer model built from the ground up in PyTorch, providing full transparency and control over every architectural component.
- **Japanese Linguistic Focus**: Specially designed to address the unique challenges of Japanese-to-English translation, including contextual particle handling, agglutinative verb forms, and significant syntactic restructuring.
- **Custom Dual Tokenization**: Independently trained BPE tokenizers for Japanese and English, optimized for the specific vocabulary and subword patterns of the training corpus.
- **Comprehensive Analysis Suite**: Built-in tools for detailed performance evaluation, error analysis, and linguistic profiling to understand translation failures and successes.

## 🤖 Conclusion

The model successfully demonstrates the Transformer's core capabilities for Japanese-English translation while providing clear insights into architecture behavior and linguistic challenges. The performance profile (high BLEU, low perplexity, but validation loss gap) serves as a precise case study in model capacity, data requirements, and generalization.

## 🤖 Future Work

- Data Expansion
- Conduction of systematic error analysis by grammatical feature


 