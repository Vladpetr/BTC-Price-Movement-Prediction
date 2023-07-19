# BTC-Price-Movement-Prediction
Chooses the best sentiment analysis method and utilizes it to predict Bitcoin price movements.

## Project Overview
The main objective of this project is to test whether it is possible to predict cryptocurrency movements by knowing the sentiment of the post that had been created sometime before the end-of-the-day price was released. This is not the first attempt to address the question of the relationship nature between cryptocurrency price movements and social media sentiments. However, all other research I encountered yielded results of a very different range, which made me think that there is a lot of uncertainty in the field. The aim of the project is to produce a new piece of evidence that can provide the computer science community with more information on the abovementioned topic.

## Data
The size of some datasets used in this project is large. Thus, I stored all relevant data <a href="https://drive.google.com/drive/folders/1IDDmGVNU-lqZvZ8wWydpTWXg0BLbj-iu?usp=sharing">here</a>. Feel free to use the raw or processed/transformed data to reproduce the outcomes.

## Models and Approaches
The following tasks were completed:
* [x] Created multiple sentiment analysis models (rule-based, LSTM, transformer) and compare them with the help of a compiled dataset.
* [x] Chose the best-performing model, tested it on a new dataset of ~2.5M Bitcoin-related tweets.
* [x] Observed how the model predictions were related to the cryptocurrency movements and discussed the implications of conducted work.
