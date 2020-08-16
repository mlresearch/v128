---
title: BERT-based conformal predictor for sentiment analysis
abstract: We deal with the Natural Language Processing (NLP) task of Sentiment Analysis
  (SA) on text, by applying Inductive Conformal Prediction (ICP) on a transformers
  based model. SA, which is the interpretation and classification of emotions, also
  referred to as emotional artificial intelligence, can be set up as a Text Classification
  (TC) problem. Transformers are deep neural network models based on the attention
  mechanism and make use of transfer learning by being pretrained on a large unlabeled
  corpus. Transformer based models have been the state of the art for dealing with
  various NLP tasks ever since they were proposed at the end of 2018. Our classifier
  consists of the BERT model for turning words into contextualized word embeddings
  with parameters fine-tuned on the used corpus and a fully connected output layer
  for performing the classification task. We examine the performance of the underlying
  BERT model and the proposed ICP on the Large Movie Review dataset consisting of
  50000 movie reviews. The results show that the good performance of the underlying
  classifier is carried on to the ICP extension without any substantial accuracy loss
  while the provided prediction sets are tight enough to be useful in practise.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: maltoudoglou20a
month: 0
tex_title: BERT-based conformal predictor for sentiment analysis
firstpage: 269
lastpage: 284
page: 269-284
order: 269
cycles: false
bibtex_author: Maltoudoglou, Lysimachos and Paisios, Andreas and Papadopoulos, Harris
author:
- given: Lysimachos
  family: Maltoudoglou
- given: Andreas
  family: Paisios
- given: Harris
  family: Papadopoulos
date: 2020-08-16
address: 
publisher: PMLR
container-title: Proceedings of the Ninth Symposium on Conformal and Probabilistic
  Prediction and Applications
volume: '128'
genre: inproceedings
issued:
  date-parts:
  - 2020
  - 8
  - 16
pdf: http://proceedings.mlr.press/v128/maltoudoglou20a/maltoudoglou20a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
