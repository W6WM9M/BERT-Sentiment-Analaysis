# CX4042 Neural Networks and Deep Learning Project: Sentiment Analaysis

<p align="justify">This is a project done for the module CX4042 Neural Networks and Deep Learning conducted by Nanyang Technological University (NTU), Singapore.</p> 

<p align="justify">Text sentiment analysis refers to identification of sentiments, usually positive or negative, expressed in text or document. </p> 

This project aims to tackle the following problems:
<ol>
  <li>To deal with domain adaptation, that is, how can one adapt a network train on one domain to work in another domain</li>
  <li>To avoid using recurrent networks to speed up computations</li>
  <li>To deal with small datasets, that is, with insufficient number of training samples</li>
</ol>

<p align="justify">To fulfill the requirements of the project, we decided to use Google's pretrained BERT-base-uncased checkpoints and finetuned it on three different datasets:
<ul>
  <li><a href="https://huggingface.co/datasets/sst2">Stanford Sentiment Treebank v2 (SST2)</a></li>
  <li><a href="https://huggingface.co/datasets/imdb">IMDb movie review dataset</a></li>
  <li><a href="https://huggingface.co/datasets/yelp_review_full">Yelp review dataset</a> </li>
</ul>
</p>
<p align="justify">
Severe overfitting was observed and we decided to investigate the effects of the following modification to reduce overfitting:
<ol>
  <li>Parameter Freezing</li> 
  <li>Increasing Dropout Probability</li> 
  <li>Increasing Dataset Size </li>
</ol>
</p>

<p align="justify">We also investigate the effects of varying BERT's input sequence length on the accuracy performance for sentiment analysis. <p>
