# Hangman Challenge : Find missing characters in a given word

- Attempt to use Pytorch transformers to train letters in a word to predict missing characters.
- Uses`attention mechanism` to predict the next letter token given a series of letters.
- Developed 2 main models : forward fill in the blank predictor, backward fill predictor.

```
Input :  borewel_
Output : l 
```

## Architecture
- 26 characters + 1 "E"  =  27 tokens in vocabulary 
- 3 transformer layers

# TODO
- Testing Metrics : Accuracy, Precision, Recall
- Different Model Architectures
- Finish BERT Model and any character location function
