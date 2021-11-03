# Natural-language-processing

This repository contains some of my Natural language processing projects, described below.

## Tweet sentiment recognition:

In this project, I use Tensorflow to develop an LSTM-based deep learning pipeline to detect tweet sentiment. I pre-process the tweet emotion dataset, train and evaluate my learning model on the tweet emotion dataset and then serve my model using Flask as a web app to detect sentiment of a user's tweet. Instructions to run the program are below:

1. Open the Colab notebook link in the *Tweet_Emotion_recognition.ipynb* file to run the program in Google Colab.
2. Upload the *templates.zip* and *static.zip* folders given in this repository to the home directory of the Colab notebook opened. The *templates.zip* and *static.zip* folders contain the html and css files used to format and create the Flask web app 
3. Run the cells in the Colab notebook opened.

## Finetuned BERT for text classification:

In this project, I do the following:
- Build TensorFlow Input Pipelines for Text Data with the tf.data API
- Tokenize and Preprocess text from the Quora Insincere Questions Dataset for BERT classification.
- Fine-tune and evaluate BERT for text classification with TensorFlow 2 and TF Hub

Instructions to run the program are below:
1. Open the Colab notebook link in the *Fine_Tune_BERT_for_Text_Classification_with_TensorFlow.ipynb* file to run the program in Google Colab.
2. Run the cells in the Colab notebook opened.
