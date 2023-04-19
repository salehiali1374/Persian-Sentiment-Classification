#Persian Sentiment Analysis with BERT

##Introduction

Sentiment analysis is a common application of natural language processing, which involves classifying text into different categories based on the sentiment expressed in the text. In this project, we have developed a Persian sentiment analysis model using the BERT (Bidirectional Encoder Representations from Transformers) algorithm. The dataset used in this project is the SnappFood Persian Sentiment Analysis dataset from Kaggle, which contains labeled text data with 'SAD' and 'HAPPY' labels.

##Methodology

We used BERT for classification, which is a state-of-the-art algorithm for natural language processing tasks. We used the bert-fa-base-uncased model, which is a pre-trained BERT model for Persian language, provided by the Hugging Face library. We fine-tuned this model on the SnappFood dataset using PyTorch and achieved a high accuracy of [87.47%].

##Results

Our Persian sentiment analysis model achieved a high accuracy of [87.47%] on the SnappFood dataset. This high accuracy indicates that the model is effective at classifying text into happy and sad categories based on the sentiment expressed in the text. To further evaluate the performance of our model, we generated a confusion matrix, as shown below:

![confusion matrix](https://github.com/salehiali1374/Persian-Sentiment-Classification/blob/main/Confusion%20matrix.jpg)

As we can see from the confusion matrix, our model has high precision and recall for both happy and sad categories. This indicates that our model is effective at distinguishing between happy and sad text data.

##Conclusion

In conclusion, we have developed a Persian sentiment analysis model using BERT and achieved a high accuracy on the SnappFood dataset. This model has high precision and recall for both happy and sad categories, and can be used for various downstream applications, such as sentiment analysis of customer reviews for businesses operating in Persian-speaking countries. We plan to continue refining this model and exploring its potential applications in the future.