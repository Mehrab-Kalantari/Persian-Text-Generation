# Persian News Prediction Using GRU Model
In this notebook, a model is developed to generate persian news using GRU units. The model is then trained on Persian Wikipedia Dataset.

[Dataset on kaggle](https://www.kaggle.com/datasets/miladfa7/persian-wikipedia-dataset)

## About Dataset
The dataset is huge so our model was trained on a small sample.


## Encoding Text
At first, we extract all vocabularies and assign a number to each of them. 
* char2index list is used for encoding
* index2char list is used for text generation 


Before feeding data to the model, data is converted into consecutive sequences.

## Modeling
A large model with 1024 GRU units was created with a dense layer at the end to predict the probability of each character.


## Prediction
At the end, the model can generate text from a prompt.
