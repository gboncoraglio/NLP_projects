## Neural network-based Transition-Based Dependency Parsing
A dependency parser analyzes the grammatical structure of a sentence, establishing relationships between head words, and words which modify those heads. 

This project involves implementing a transition-based parser, which incrementally builds up a parse one step at a time. 

At every step it maintains a partial parse, which is represented as follows:
- A stack of words that are currently being processed. 
- A buffer of words yet to be processed.
- A list of dependencies predicted by the parser.

This project involves implementing a neural-network based dependency parser, with the goal of maximizing performance on the UAS (Unlabeled Attachemnt Score) metric.
This project was done when studying for the course CS224n: Natural Language Processing with Deep Learning.

