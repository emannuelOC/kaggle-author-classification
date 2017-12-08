# kaggle-author-classification
Repository for the code and submissions to the Author Identification competition.

## First tries:
[x] Simple FFNN, with Word2Vec (100-dimension vectors) trained on the data itself;
[ ] Less simple FFNN, again with w2v (100d vectors) trained on the data itself

## Possibilities

### Small changes
[ ] Add dropout and/or early stopping to avoid overfitting

### Embeddings
[ ] Try changing the hyperparameters for the vector generation (smaller vectors)
[ ] Try changing the hyperparameters for the vector generation (bigger vectors) 
[ ] Try pretrained vectors (since maybe the data isn't enough to train the vectors)
[ ] Try GloVe (although it does make sense to use w2v since I guess the three authors are closer semantically than syntactically
[ ] Try some local representation.. well, who knows? maybe this is not the case to use those fancy embeddings, right? 

### Architectures
[ ] Try RNN
[ ] Try LSTM
