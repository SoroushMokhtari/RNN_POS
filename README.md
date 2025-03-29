# Building an RNN from Scratch - Application for Part-Of-Speech (POS) Tagging

![Alt text](./Images/RNN_POS.png)

Starting with just NumPy and basic calculus, we will implement a vanilla Recurrent Neural Network entirely from scratch. This self-built RNN will then be applied to the Part-Of-Speech tagging problem.

## Recurrent Neural Networks (RNNs)
Recurrent Neural Networks (RNNs) are a type of neural network designed to process sequential data. Unlike standard feedforward networks, RNNs have internal "memory" in the form of hidden states that allow them to maintain information about past inputs in the sequence. This makes them well-suited for tasks where the order and context of data points are important, such as natural language processing, time series analysis, and speech recognition. They achieve this by feeding the output of a layer back into the input of the same layer (or a previous layer) at the next time step.

## Part-Of-Speech (POS) Tagging
Part-of-Speech (POS) tagging is the process of labeling each word in a text (like a sentence) with its corresponding grammatical category. These categories, also known as parts of speech or word classes, include things like nouns, verbs, adjectives, adverbs, pronouns, prepositions, etc. The goal is to identify the syntactic role of each word in the sentence, which is crucial for understanding its meaning and structure.

## The Game Plan
- Build an RNN cell
- Stack them together
- Make it learn through backpropagation
- Apply it to POS tagging
