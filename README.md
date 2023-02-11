## Language Modelling using Feedforward Neural Network
This notebook implements a word-level language modelling using Feedforward Neural Network for Zulu language. The implementation is a trigram model (using two words of context as input to the feedforward network). Data is tokenized and unknown words are handled by replacing all words that occur only once in the training data with UNK token.The language model is evaluated using perplexity. 

### Install these packages
- Python 3
- Pytorch
- NumPy
- Matplotlib
- Jupyter Notebook