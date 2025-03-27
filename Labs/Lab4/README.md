#Text Generation with RNNs

Overview

This project explores text generation using deep learning models, specifically Recurrent Neural Networks (RNNs). The goal is to train a model to predict the next word in a sequence, generating meaningful text.

Dataset

The dataset consists of Shakespeare's works, which are tokenized to train the model. This allows the model to learn the structure and style of the text.

Model Architectures

The project implements three types of RNN models:

LSTM (Long Short-Term Memory)

GRU (Gated Recurrent Unit)

Bidirectional RNN

Training Process

The text is converted into numerical sequences and used as input for the models. The models are trained using an optimizer and loss function to improve their predictions.

Evaluation

The models are evaluated based on their ability to generate coherent text. Metrics like perplexity and BLEU score help measure their performance.

Text Generation

Once trained, the models can generate new text based on a given input. The output is analyzed for fluency and relevance.

Conclusion

This project compares different RNN architectures for text generation, analyzing their effectiveness in creating Shakespearean-style text.
