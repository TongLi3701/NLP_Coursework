# Sentence-level QE Task 2020

This repository provides our code for NLP CO490 coursework 2020 at Imperial College London. In this task, we used the English-Chinese corpus and achieved a Pearson score of 0.4327 as our best performance on the hidden test set. The code can run on Colab.

## Table of Contents
### 1. Data Collection 
### 2. Data Preprocessing
* English 
* Chinese

### 3. Embedding Methods
* Sentence Embedding
    * SentenceTransformers
    * BERT
* Word Embedding
    * Word2Vec and GloVe
    * BERT

### 4. Models 
* SVR
* Feedforward Neural Network
* Recurrent Neural Network with LSTM (Word2Vec and GloVe)
* Recurrent Neural Network with LSTM (BERT)

## Getting Started
Upload this notebook on Colab and then upload the dataset to the default folder.
The *Download and Import Libraries* and *Import Data* should be run at first.

## Pre-processing 
Please run this part after importing data if you want the corpus to be pre-processed. In the *Embedding* section below, you can choose to either use the raw corpus or the pre-processed corpus.


## Embedding 
There are two types of embedding methods: word embedding and sentence embedding. You can choose one of the embedding methods before running the model.


## Model Selection
* SVR: You can choose any one of the embedding methods before running the SVR model. The input of this model can be a sequence of word vectors or a sentence vector.

* FNN: The input of this model should be a result of sentence embeddings. You can choose SentenceTransformers or BERT as you wish.

* RNN with LSTM: You can choose GloVe or BERT embedding method as you wish beforehand.