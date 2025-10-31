# Hangman Challenge : Find missing characters in a given word

- Attempt to use Pytorch transformers to train letters in a word to predict missing characters.
- Developed 2 main models : forward fill in the blank predictor, backward fill predictor

```
Input :  borewel_
Output : l 
```

## Architecture
- 26 characters + 1 "E"  =  27 tokens in vocabulary 
- 3 transformer layers


