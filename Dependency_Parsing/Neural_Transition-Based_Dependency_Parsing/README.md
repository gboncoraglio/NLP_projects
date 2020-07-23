A dependency parser analyzes the grammatical structure of a sentence, establishing relationships between head words, and words which modify those heads. 

This project involves implementing a transition-based parser, which incrementally builds up a parse one step at a time. 

At every step it maintains a partial parse, which is represented as follows:
- A stack of words that are currently being processed. 
- A buffer of words yet to be processed.
- A list of dependencies predicted by the parser.

We use a neural network (pytorch) for predicting which transition should be applied next to a partial parse.
This project was done when studying for the course CS224n, CS224n: Natural Language Processing with Deep Learning.

