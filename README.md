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

### Add and Normalize

This part of the transfomer makes the training much faster. This part also ensures that vectors are updated by attention layers rather than replace them.

### Attention Layers

This is broken into four categories of attention layers: base attention layer, cross attention layer, global self attention layer, and casual self attention layer. The cross attention layer connects the encoder and the decoder. The global self attention layer deals with context sequences and propogating information. The self attention layer is similar to the global self attention layer, but deals with the output.

### Feed Forward/Encoder

### Decoder

### Training/Testing

After the encoder and the decoder has been constructed, the program then gives the transformer specific parameters, and the program uses those to build a model, train a model, test the model, and the examine the results.
