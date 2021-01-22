# generate_tv_scripts

This project aims to generate user's own new fake "Seinfeld" TV scripts using Neural Network trained on the dataset from "Seinfeld" TV scripts from 9 seasons.

RNNs in particular GRU is used to build the Neural network along with the fully connected layer to predict the output class scores of the next word in an input sequence of words.This input sequence of words is converted into embeddings using word2vec model for dimensionality reduction

