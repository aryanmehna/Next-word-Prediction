# Next-word-Prediction

## Project Description
In this Project i used google colab as well as jupyter notebook. we used text file (pride and prejudice) as data.
This project basically predicts the next word with the help of 3 last words(3 input words).

## Why LSTM ?
We used LSTM in this project because LSTM model uses Deep learning with a network of artificial “cells” that manage memory, making them better suited for text prediction than traditional neural networks and other models. LSTM can store past important information and forget the information that is not.
LSTM has memory cells that can remember the previous context

## Tokenization
Applied tokenization on the text using tokenizer. Tokenization is basically breaking the raw text into small chunks. These chunks are called tokens, and these tokens helps in understanding the context and to develop the model using NLP.
We converted these tokens into sequence using texts_to_sequences.

## Model 
In this model, there are 5 layers-1 embedding layer for the input, 2 LSTM layers layers, 2 dense layers.
Ran the model with 70 epochs
 
## Layer and Activation Function
Embedding Layer = The Embedding layer is defined as the first hidden layer of a network. Embedding layer enables us to convert each word into a fixed length vector of defined size. The fixed length of word vectors helps us to represent words in a better way along with reduced dimensions.

LSTM layers = LSTMs use a series of 'gates' which control how the information in a sequence of data comes into, is stored in and leaves the network.

Dense layer = Dense Layer is simple layer of neurons in which each neuron receives input from all the neurons of previous layer. A dense layer is a layer that is deeply connected with its preceding layer which means the neurons of the layer are connected to every neuron of its preceding layer.

Activation Function = softmax and relu

ReLU (Rectified Linear Unit) = Advantage of ReLU function over other activation functions is that it does not activate all the neurons at the same time. ReLU in hidden layer to avoid vanishing gradient problem and better computation performance

Softmax = We use the function at last layer of neural network which calculates the probabilities distribution of the event over ’n’ different events. The main advantage of the function is able to handle multiple classes.


