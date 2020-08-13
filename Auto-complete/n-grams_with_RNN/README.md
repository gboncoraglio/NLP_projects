The task of this project is to predict the next set of characters using the previous characters. 
- Although this task sounds simple, it is pretty useful.
- start by converting a line of text into a tensor
- Then create a generator to feed data into the model
- train a neural network in order to predict the new set of characters of defined length. 
- use embeddings for each character and feed them as inputs to your model. 
    - Many natural language tasks rely on using embeddings for predictions. 
- model will convert each character to its embedding, run the embeddings through a Gated Recurrent Unit `GRU`, and run it through a linear layer to predict the next set of characters.

The figure below gives a summary: 
- get the embeddings;
- Stack the embeddings on top of each other;
- Run them through two layers with a relu activation in the middle;
- Finally, compute the softmax. 

To predict the next character:
- Use the softmax output and identify the word with the highest probability.
- The word with the highest probability is the prediction for the next word.
