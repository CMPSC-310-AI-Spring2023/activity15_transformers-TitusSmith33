[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/ymop5HUw)
# CMPSC 310 Activity 15

## Deadline: April 12 by 9:50am

## Assignment

 For this activity follow [Neural machine translation with a Transformer and Keras](https://www.tensorflow.org/text/tutorials/transformer).

## Submission

Submit completed Colab notebook showing generated output.

## Data

The data found in this tutorial is a data set from Tensor Flow of a data set full of Portuguese-English translations. This dataset has about 52,000 training sets, 1,200 validation sets, and 1,800 test cases. The program then breaks down all the words and gives them numerical value and tries to rebuild it back up to human readable text, a process called tokenizing. Lastly, it tests the data set to ensure that the data has been processed correctly.

## Transformer Components

This program uses a transformer model to train the data, and there is a lot that goes into a transformer model, so I have broken it up into categories:

### Positional Encoding Layer

Takes in both the Portuguese and English input tokens and converts them to vectors.

### Add and Norm

### Attention Layers

### Feed Forward/Encoder

### Decoder

### Dense Layer

### Training/Testing
