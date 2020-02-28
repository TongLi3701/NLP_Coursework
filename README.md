# Sentence-level QE Task 2020

This repository provides our code for NLP CO490 coursework 2020 at Imperial College London. In this task, we used the English-Chinese corpus and achieved a Pearson score of **0.4327** as our best performance on the hidden test set. The code can run on Colab. 

In this repository, we present eight models:

* [SVR+Sentence_embed_sentence_transformer+raw.ipynb](https://github.com/TongLi3701/NLP_Coursework/blob/master/SVR%2BSentence_embed_sentence_transformer%2Braw.ipynb)
* [SVR+Sentence_embed_sentence_transformer+pre_process.ipynb](https://github.com/TongLi3701/NLP_Coursework/blob/master/SVR%2BSentence_embed_sentence_transformer%2Bpre_process.ipynb)
* [FNN+Sentence_embed_sentence_transformer+raw.ipynb](https://github.com/TongLi3701/NLP_Coursework/blob/master/FNN%2BSentence_embed_sentence_transformer%2Braw.ipynb)
* [RNN+Word_embed_GloVe_Word2Vec+pre_process.ipynb](https://github.com/TongLi3701/NLP_Coursework/blob/master/RNN%2BWord_embed_GloVe_Word2Vec%2Bpre_process.ipynb)
* [SVR+Sentence_embed_Bert_multilingual+raw.ipynb](https://github.com/TongLi3701/NLP_Coursework/blob/master/SVR%2BSentence_embed_Bert_multilingual%2Braw.ipynb)
* [SVR+Sentence_embed_Bert_base+raw](https://github.com/TongLi3701/NLP_Coursework/tree/master/SVR%2BSentence_embed_Bert_base%2Braw)
* [SVR+Sentence_embed_Bert_large+raw](https://github.com/TongLi3701/NLP_Coursework/tree/master/SVR%2BSentence_embed_Bert_large%2Braw)
* [RNN+Word_embed_Bert+pre_process.ipynb](https://github.com/TongLi3701/NLP_Coursework/blob/master/RNN%2BWord_embed_Bert%2Bpre_process.ipynb)

The titles describe *which model we use* + *which embedding method we choose* + *whether we use pre-processing or not*.

## Getting Started
Upload one ipython notebook file to Colab and upload the files in the *dataset* folder.

## Directly Runnable Models

* [SVR+Sentence_embed_sentence_transformer+raw.ipynb](https://github.com/TongLi3701/NLP_Coursework/blob/master/SVR%2BSentence_embed_sentence_transformer%2Braw.ipynb)
* [SVR+Sentence_embed_sentence_transformer+pre_process.ipynb](https://github.com/TongLi3701/NLP_Coursework/blob/master/SVR%2BSentence_embed_sentence_transformer%2Bpre_process.ipynb)
* [FNN+Sentence_embed_sentence_transformer+raw.ipynb](https://github.com/TongLi3701/NLP_Coursework/blob/master/FNN%2BSentence_embed_sentence_transformer%2Braw.ipynb)
* [RNN+Word_embed_GloVe_Word2Vec+pre_process.ipynb](https://github.com/TongLi3701/NLP_Coursework/blob/master/RNN%2BWord_embed_GloVe_Word2Vec%2Bpre_process.ipynb)
* [SVR+Sentence_embed_Bert_multilingual+raw.ipynb](https://github.com/TongLi3701/NLP_Coursework/blob/master/SVR%2BSentence_embed_Bert_multilingual%2Braw.ipynb)

Simply run all the modules and we could obtain the Pearson results of the models on the validation dataset.

## Models Using two BERT models

* [SVR+Sentence_embed_Bert_base+raw](https://github.com/TongLi3701/NLP_Coursework/tree/master/SVR%2BSentence_embed_Bert_base%2Braw)
* [SVR+Sentence_embed_Bert_large+raw](https://github.com/TongLi3701/NLP_Coursework/tree/master/SVR%2BSentence_embed_Bert_large%2Braw)

	1. First we run till the *Save English results* module.

	2. Download the produced *english_train_berteb.csv*, *english_dev_berteb.csv*, *english_test_berteb.csv*. 

     The files are also provided in the folders given above. **We can start from step 4 if we use the files provided.**

	3. Disconnect the notebook in Colab.

	4. Reconnect and upload the files in *dataset* folder and the csv files downloaded in step 2.

	5. Run the modules **before the *English Model* module** and the modules **following the *Chinese Model* module**. 

     Finally we obtain the Pearson score on the validation dataset, along with the *en-zh_svr.zip* file (results on the test dataset) that can be handed in to CodaLab.

* [RNN+Word_embed_Bert+pre_process.ipynb](https://github.com/TongLi3701/NLP_Coursework/blob/master/RNN%2BWord_embed_Bert%2Bpre_process.ipynb)
  
  1. Copy the [folder with **BERT word embedding results**](https://drive.google.com/open?id=1kreg-Fim20ITvQeHmDU0jYbED8ATAKnz) into Google drive.
  2. Start running from the module *Model: LSTM (BERT word embedding)*.

## Authors

* aw1019, *email*: <aoyu.wang19@imperial.ac.uk>

* xc2019, *email*: <xinyuan.chen19@imperial.ac.uk>

* tl1219, *email*: <tong.li19@imperial.ac.uk>

  