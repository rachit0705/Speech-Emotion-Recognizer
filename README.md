# Speech-Emotion-Recognizer

## What is Speech Emotion Recognition?
Speech Emotion Recognition, is the act of attempting to recognize human emotion and affective states from speech. This is capitalizing on the fact that voice often reflects underlying emotion through tone and pitch. This is also the phenomenon that animals like dogs and horses employ to be able to understand human emotion.

## What is librosa?
librosa is a Python library for analyzing audio and music. It has a flatter package layout, standardizes interfaces and names, backwards compatibility, modular functions, and readable code. Further, in this Python mini-project, we demonstrate how to install it (and a few other packages) with pip.

## Objective
To build a model to recognize emotion from speech using the librosa and sklearn libraries and the RAVDESS dataset.
In this Python project, we will use the libraries librosa, soundfile, and sklearn (among others) to build a model using an MLPClassifier. This will be able to recognize emotion from sound files. We will load the data, extract features from it, then split the dataset into training and testing sets. Then, we’ll initialize an MLPClassifier and train the model. Finally, we’ll calculate the accuracy of our model.

## The Dataset
For this Python project, we’ll use the RAVDESS dataset; this is the Ryerson Audio-Visual Database of Emotional Speech and Song dataset, and is free to download. This dataset has 7356 files rated by 247 individuals 10 times on emotional validity, intensity, and genuineness. 

## Model building and evaluation
In this project, we used an MLPClassifier for this and made use of the soundfile library to read the sound file, and the librosa library to extract features from it. And finally the model delivered an accuracy of 78% which is quite acceptable and trying to optimze it further.
