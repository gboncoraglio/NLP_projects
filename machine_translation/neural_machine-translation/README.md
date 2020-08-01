### Neural Machine Translation with RNNs

In Machine Translation, our goal is to convert a sentence from the source language (e.g. Spanish) to the
target language (e.g. English). In this project, we will implement a sequence-to-sequence (Seq2Seq)
network with attention, to build a Neural Machine Translation (NMT) system. The proposed NMT system uses a Bidirectional LSTM
Encoder and a Unidirectional LSTM Decoder.

Model is trained on Azure, using pyTorch and GPUs for faster training.
Training takes approximately 3.5 hours.
For the evaluation model, model’s corpus BLEU Score is roughly 22.

![Alt text](img1.png?raw=true "Title")
