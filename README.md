# Spam message Classifier

## Goal:
 The Aim of this machine learning model is to find the spam message.For this project i used Machine Learning with NLP
 
## NLP PipeLine:
![1 CbzCcP3XFtYVJmWowZLugQ](https://user-images.githubusercontent.com/61903698/134461144-5f71a441-5b74-4d83-a3ce-8d12823aea25.png)

## Tokenization:
![maxresdefault](https://user-images.githubusercontent.com/61903698/134461654-73f03562-ec9f-4164-9be1-cd1f37bbd9d2.jpg)

Tokenization is a way of separating a piece of text into smaller units called tokens.
## text_cleaning:
The dataset has several punctuations. Punctuations are often unnecessary as it doesn’t add value or meaning to the NLP model. The “string” library has 32 punctuations. The punctuations are:
 
                 import string
                 string.punctuation
                 
## Stopwords
![stop-word](https://user-images.githubusercontent.com/61903698/134461738-aa31ae44-c394-43cc-8123-935b9f20cf57.jpg)

Stop words are irrelevant words that won’t help in identifying a text as real or fake. We will use “nltk” library for stop-words and some of the stop words in this library are :

                               stopword = nltk.corpus.stopwords.words('english'


##  Stemming or Lemmatization:

Stemming and Lemmatizing is the process of reducing a word to its root form. The main purpose is to reduce variations of the same word, thereby reducing the corpus of words we include in the model. The difference between stemming and lemmatizing is that, stemming chops off the end of the word without taking into consideration the context of the word. Whereas, Lemmatizing considers the context of the word and shortens the word into its root form based on the dictionary definition. Stemming is a faster process compared to Lemmantizing. Hence, it a trade-off between speed and accuracy.

![maxresdefa](https://user-images.githubusercontent.com/61903698/134461955-1a877f69-f60d-42b0-b652-70b2bd892bfa.jpg)

## Model Buillding 
![1 dWY7adQ62NDn_w_sc4lAKw](https://user-images.githubusercontent.com/61903698/134462100-eb766cb0-d6af-40bc-b065-e929778304fc.png)

After text preprocessing we convert the sentences into vector after we define the dependent and independent features.
split the dataset into train and test and we can use any ml algorithm for train the model.

## Evaluation:
For this usecase we use a accuracy score because it is the classification problem.so we use confusion_matrix and accuracy_score.

## Deployment:
![images](https://user-images.githubusercontent.com/61903698/134462616-dbb8e3b4-ab26-45a8-9b66-5fe4e0d66630.png)

for a deployment i use Django,HTML,CSS,Bootstrap with heroku.




