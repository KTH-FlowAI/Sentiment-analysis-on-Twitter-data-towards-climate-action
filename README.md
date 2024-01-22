# Sentiment analysis on Twitter data towards climate action

## Introduction 
The code in this repository features sentiment analysis with VADER, TextBlob and tranfer learning wth BERT + trained regression model. The sentiment is positive, negative and neutral. The BERT-based model is binary,positive/negative. 
For more details regarding methods, result and models see the paper ["Sentiment analysis on Twitter data towards climate action", Emelie Rosenberg, Carlota Tarazona, Fermín Mallor, Hamidreza Eivazi, David Pastor-Escuredo, Francesco Fuso-Nerini, Ricardo Vinuesa](https://doi.org/10.1016/j.rineng.2023.101287)

This site was built using [GitHub Pages](https://pages.github.com/).


This repository is transferred from [the public repository](https://github.com/rooosenberg/Sentiment-analysis-on-Twitter-data-towards-climate-action). The transfer of this repository is conducted in accordance with the permission granted by the original author. For inquiries regarding this repository, please contact [author](https://github.com/rooosenberg).

## Data
- Training: The training of the Regression model was done with the Kaggle dataset [Sentiment140](https://www.kaggle.com/datasets/kazanova/sentiment140).
- Collected data: It was collected with the python package, Tweepy. For the collecte draw data see [Google drive file](https://drive.google.com/drive/folders/1CsGv0CyDpat7TNP4wRuXDuqUBcpkABUj?usp=drive_link). 
- Annotated data: 247 tweets was annoteded as positive, neutral and negative.  

## BERT-model
The TweetBert model was used for tokanization. For more information about the model see [Hugging Face model card](https://huggingface.co/docs/transformers/model_doc/bertweet). 
The BERT-model was runned on GPU. 

## Regression model
The model can be found under code/Sentiment analysis/Model/. 
The regression model was trained on Google Colab. 



