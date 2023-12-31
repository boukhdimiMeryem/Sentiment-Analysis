# Sentiment-Analysis
This project performs Sentiment analysis on data in Moroccan dialect (Darija), it involves leveraging advanced techniques in natural language processing (NLP) and machine learning. The BERT (Bidirectional Encoder Representations from Transformers) model is particularly well-suited for this task.

# BERT Model
![image](https://github.com/boukhdimiMeryem/Sentiment-Analysis/assets/93484500/9cd7d09f-1ec0-48ab-a3a9-678c42e07b9d)

BERT, which stands for Bidirectional Encoder Representations from Transformers, is a powerful natural language processing (NLP) model developed by Google. It was introduced in the paper titled "BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding".

It is based on the Transformer architecture that uses self-attention mechanisms to capture relationships between words in a sequence, allowing for parallelization and more effective modeling of long-range dependencies.

The other reason why i used BERT for this project is that it has bidirectional pretraining, unlike traditional language models that are trained in a left-to-right or right-to-left manner, BERT is trained bidirectionally. It learns to predict missing words in a sentence by considering both the left and right contexts simultaneously. This bidirectional pretraining helps BERT capture richer contextual information.

# Components of the repository

The project repository includes the following components:

Dataset/: This directory holds the dataset and all features explained in Dataset_Features.txt
model_training_evaluation.ipynb: The Jupyter Notebook used for building and analyzing the sentiment classifier model.
