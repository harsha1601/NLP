## Document Classification:
The aim of the code is to find whether a message is spam or not.
It is done with the use of machine learning using nltk.

#### STEPS:
* Importing data 
* Pre-processing: In this first the words are lemmatized and converted into tokens and the stop words are neglected from the text such as 'is','this','that' etc.
* Labelling : The text from spam messages is labelled as 'spam' and the other one as 'ham'. 
* Fetaure extraction: The features used here are just bag of words which returns the number of times a word appears in the text.
* Training: The training is done using Naive Bayer Classification method.
* Evaluation: After training from the train data estimations are given to the test data and accuracy is found.
