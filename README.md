# NLP---Tensorflow
Tensorflow - Text Classification. Sentiment Analysis in IMDB dataset of tensorflow. 
- The notebooks 01_02_end explains the implementation of word encodings in NLP using the tensorflow library.

- The notebook 01_03_end covers the creation of sequences of tokens from words in a sentence.

- The notebook 01_04 explains how to manipulate sequences to make them of equal length using padding.

- The notebook 01_06 covers the data preparation step by tokenizing the headlines and creating padded sequences of news headlines.
Data preparation include the following steps:
1. Download and read the data
2. Segregate the headlines and their labels.
3. Tokenize the headlines
4. Create sequences and add padding.

- This notebook 02_02_end explains an introduction to word embeddings. We will train our own word embeddings using a simple Keras model for a sentiment classification task. Keras Sequential model has embeddings layer with embedding_dim of 16, GlobalPooling1D, Dense with 24 nodes relu activation, Dense with 1 node and softmax activation.
Steps include:
1. Downloading data from tensorflow dataset.
2. Segregating training and testing sentences & labels.
3. Data preparation to padded sequences
4. Defining out Keras model with an Embedding layer.
5. Train the model and explore the weights from the embedding layer.

- This notebook 03_02_end walks you through the implementation of an LSTM model to classify news headlines as sarcastic or not_sarcastic. We will analyse the accuracy & loss curves for training and validation sets.

