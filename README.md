# CX4042 Sentiment Analaysis

This is a project done for the module CX4042 Neural Networks and Deep Learning conducted by Nanyang Technological University (NTU), Singapore. 

Text sentiment analysis refers to identification of sentiments, usually positive or negative, expressed in text or document.

In this project, we evaluated BERT on sentiment analysis using three different datasets:
- [Stanford Sentiment Treebank v2 (SST2)](https://huggingface.co/datasets/sst2)
- [IMDb movie review dataset](https://huggingface.co/datasets/imdb)
- [Yelp review dataset](https://huggingface.co/datasets/yelp_review_full) 

We tackled the following problems: 
1. To deal with domain adaptation, that is, how can one adapt a network train on one domain to work in another domain
2. To avoid using recurrent networks to speed up computations
3. To deal with small datasets, that is, with insufficient number of training samples
4. To deal with overfitting
