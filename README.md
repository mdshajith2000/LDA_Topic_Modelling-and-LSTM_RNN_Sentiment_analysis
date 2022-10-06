# LDA_Topic_Modelling-and-LSTM_RNN_Sentiment_analysis
Application of Topic Modeling and LSTM RNN for Deep Sentiment Classification and Topic Discovery on COVID-19 Dataset

Dataset link: https://www.kaggle.com/datasets/khalidalharthi/coronavirus-posts-in-reddit-platform

LDA.ipynb - Performs Tipic modelling using latent dirichlet allocation

lstmLevi.ipynb - Perfoms sentiment analysis using LSTM-RNN

Inter-web forums and social media, such as online healthcare forums, offer a simple way for users
(people/patients) interested in health concerns to communicate and exchange information. An
epidemic of the Coronavirus was discovered in late December 2019, and owing to the virus's fast
spread in different parts of various countries, it was declared a public health emergency. Due to its
devastating effect on people's health all across the world, the World Health Organization has
declared it a pandemic. In this article, we use a Natural Language Processing technique based on
topic modelling to extract COVID-19 related remarks from internet forums and use it to generate
appropriate inferences. We also look at how to utilize an LSTM recurrent neural network to
classify COVID-19 comments by sentiment. Our findings highlight the necessity of incorporating
public opinion and appropriate computational approaches into understanding COVID-19 concerns
and guiding associated decision-making.

Algorithm
1. Collection of the dataset from Kaggle
2. Preprocessing
2.1 Removal of noise
2.2 Removal of Stop words
2.3 Tokenization
3. Extract Covid-19 related topics and analyse people's sentiment
3.1 Use LDA semantic mining for topic recommendation
3.2 Use deep learning LSTM-RNN method for comment classification
