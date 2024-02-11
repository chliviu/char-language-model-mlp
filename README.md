# char-language-model-mlp
Multilayer perceptron char language model

Based on [Bengio et al. 2003](https://www.jmlr.org/papers/volume3/bengio03a/bengio03a.pdf) paper.

Continuing the exploration of https://github.com/chliviu/char-language-model-bigram

# MLP

In the paper, the proposed solution uses words, but we'll be using characters.
Each word is associated with a 30 dimensional feature vector.
In the beginning the words are initialised completely randomly, but then we are going to tune these embeddings of words using back propagation. 
Words that have similar meaning would end up in one part of the space and words that mean different things would land on different parts of the space.
