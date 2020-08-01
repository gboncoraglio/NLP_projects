### Character-based convolutional encoder for NMT 

work based on Character-Aware Neural Language Models by Kim et al.


### Character-based LSTM decoder for NMT

It is also added a LSTM-based character-level decoder to the NMT system, based on Luong & Manning’s work. 

The main idea is that when our word-level decoder produces an <UNK> token, we run
our character-level decoder (which you can think of as a character-level conditional language model) to
instead generate the target word one character at a time. This will help us to
produce rare and out-of-vocabulary target words.

Project done while studying for the class CS 224N, Natural Language Processing with Deep Learning.

![Alt text](img1.png?raw=true "Title")

![Alt text](img2.png?raw=true "Title")
