# TextRank_Implementation

This project is an implementation of the TextRank algorithm for text summarization.

## Requirements

- Python 3.10
- PyTorch 2.0
- Transformers 4.35.0
- spaCy 3.5.0
- NLTK 3.8.1
- NumPy 1.24.2
- Pandas 2.0.1
- Scikit-learn 1.2.2
- Gensim 4.3.0

## Structure

The project contains TextRank for summarizing English and Persian documents.

We have used following embedding models for Persian Language:

- ParsBERT
- Word2Vec
- Pretrained FastText 

And the following embedding models for English Language:

- Word2Vec
- Pretrained Word2Vec
- Pretrained GLOVE
- Pretrained BERT

we also have used HAZM library for tokenization and sentence segmentation for Persian Language and we implemented ROUGE metric for evaluation.

