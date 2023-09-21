# Persian Sequence Prediction using GRU Model
In this notebook, we create a model to generate persian text using GRU model and persian wikipedia dataset

[Dataset on kaggle](https://www.kaggle.com/datasets/miladfa7/persian-wikipedia-dataset)

## About Dataset
The dataset is huge so we train our model on a small sample.


## Encoding Text
At first, we extract all vocabularies and assign a number to each of them. 
* char2index: for encoding purposes
* index2char: for text generation purposes


Before modeling, we create sequences of data.

## Modeling
We use GRU model with 1024 units and a dense layer to predict probability of each character.


## Prediction
At the end, we use our model to generate text.
