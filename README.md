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

## Dataset

We have used the following dataset for training and evaluation:

- XSUM Dataset - English(You can find it here: https://github.com/EdinburghNLP/XSum)
- BBC News Summary Dataset - English (You can find it here: https://www.kaggle.com/datasets/pariza/bbc-news-summary) 
- Mashregh News Summary Dataset - Persian (Due to the lack of dataset for Persian Language, we created our own dataset by scraping Mashregh News Website. You can find it in my Google Drive using this link: https://drive.google.com/drive/folders/1ycOu6f3427LHG1_xYK6ctAIpheYJMb20)

