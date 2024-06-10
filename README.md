# Natural-Language-Processing-NLP-in-machine-learning-algorithms
## Text Vectorization Methods in Natural Language Processing

## Table of Contents

- [One-Hot Encoding](#one-hot-encoding)
- [Bag of Words (BoW)](#bag-of-words-bow)
- [N-Grams](#n-grams)
- [TF-IDF Vectorizer](#tf-idf-vectorizer)

## One-Hot Encoding

### Purpose:
Convert text into binary vectors.

### Steps:
1. Tokenize the text into words.
2. Identify unique words in the corpus.
3. Create binary vectors where each position corresponds to a unique word, with 1 indicating the presence of the word and 0 indicating absence.

## Bag of Words (BoW)

### Purpose:
Convert text into frequency vectors.

### Steps:
1. Tokenize the text into words.
2. Identify unique words in the corpus.
3. Create vectors where each position corresponds to a unique word, with values indicating the count of each word in the document.

## N-Grams

### Purpose:
Capture contiguous sequences of n words.

### Steps:
1. Tokenize the text into words.
2. Generate n-grams (e.g., bigrams, trigrams) from the tokenized text.
3. Identify unique n-grams in the corpus.
4. Create frequency vectors for each document based on the n-grams.

## TF-IDF Vectorizer

### Purpose:
Reflect the importance of words in a document relative to the entire corpus.

### Steps:
1. Tokenize the text into words.
2. Calculate term frequency (TF) for each word in a document.
3. Calculate inverse document frequency (IDF) for each word in the corpus.
4. Multiply TF by IDF to get the TF-IDF score.
5. Create vectors for each document where each position corresponds to a unique word, with values indicating the TF-IDF score.
