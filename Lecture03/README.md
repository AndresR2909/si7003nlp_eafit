# SI7003 NLP lecture03

# Introduction to Word Embeddings and Sequence Models

This class aims to provide a comprehensive understanding of how text is processed in machine learning, focusing on fundamental techniques such as **Word2Vec, Tokenizers, Recurrent Neural Networks (RNNs), and Attention Mechanisms**. The goal is to equip students with the knowledge to effectively represent text data and build models capable of handling sequential information.

## Topics Covered

### 1. Word2Vec: Learning Word Representations
- Understanding word embeddings and their importance in NLP.
- Word2Vec: Continuous Bag of Words (CBOW) and Skip-Gram models.
- Training word embeddings using neural networks.
- Visualizing embeddings and exploring relationships between words.
- Limitations of Word2Vec and advancements in word representation.

### 2. Tokenizers: Preprocessing Text for Deep Learning
- Why tokenization is essential in NLP.
- Different types of tokenizers:
  - Subword-based tokenization (Byte Pair Encoding, WordPiece, Unigram).
  - Character-level tokenization.
- Implementing tokenization using the Hugging Face `tokenizers` library.
- How tokenization impacts model performance.

### 3. Recurrent Neural Networks (RNNs): Modeling Sequences
- The need for sequential modeling in NLP.
- Basics of RNNs and how they process sequences.
- Vanishing gradient problem and the limitations of RNNs.
- Long Short-Term Memory (LSTM) and Gated Recurrent Units (GRUs) as solutions.

### 4. Attention Mechanisms: Enhancing Sequence Modeling
- Motivation behind attention: Handling long-range dependencies.
- How attention works: Weighted sum of input sequences.
- Self-Attention and its role in modern NLP.
- Transformer architecture: Moving beyond RNNs.

## Learning Outcomes
By the end of this class, students should be able to:
- Understand and apply word embedding techniques like Word2Vec.
- Implement different tokenization strategies for NLP models.
- Leverage attention mechanisms to improve sequence processing.

This class serves as a foundation for more advanced topics in Natural Language Processing, such as Transformers, Large Language Models (LLMs), and state-of-the-art NLP applications.

## Prerequisites
- Basic understanding of Python and machine learning.
- Familiarity with deep learning libraries such as TensorFlow or PyTorch.
- Some experience with NLP concepts is helpful but not required.

## Tools and Libraries
- `gensim` for Word2Vec.
- `tokenizers` from Hugging Face.
- `torch` for implementing RNNs.
- `transformers` for working with attention-based models.

---
**Instructor Notes:** This class is designed to be interactive, with coding examples and hands-on exercises. Make sure to follow along with the provided notebooks for a deeper understanding!
