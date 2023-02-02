# NLU Language Modeling project

This is the repository for the NLU's course project.

Language modeling is a fundamental task in Natural Language Processing (NLP) that aims to predict the likelihood of words in a sentence, as well as generate new words based on a given context.
The goal of this task is to train a model that can produce new meaningful text according to the user's needs.
It is essential to train the model on a massive corpus of text, such as books, articles or web pages.
This is because, during the training phase, the language model learns the dependencies and probability distributions between words, which enables it to generate text that is coherent and meaningful.

The dataset used for training and evaluating the models used in this project is a preprocessed version of the [Penn Treebank (PTB)](https://catalog.ldc.upenn.edu/LDC99T42).
This version of PTB contains only lower-cased words, numbers are replaced with N, rare words are replaced by unk and the vocabulary consists of the most frequent 10k words.
This is one of the most popular datasets used by the NLP community, and it is used for both character-level and word-level language modeling.
The dataset was created by the University of Pennsylvania by collecting articles from the Wall Street Journal.

The models presented in this project are:
- LSTM vanilla;
- LSTM with improvements proposed by the paper [Regularizing and Optimizing LSTM Language Models](https://arxiv.org/abs/1708.02182);
- GPT-2 provided by [Hugging Face](https://huggingface.co/docs/transformers/model_doc/gpt2), specifically zero-shot analysis and finetuning on PTB dataset.

At this link are available the weights of the models: https://drive.google.com/drive/folders/159Rtz603byQKyNomoKQnxVtbCfX0cpfZ?usp=sharing
