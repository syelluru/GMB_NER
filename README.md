# GMB_NER
This repository assumes the [Groningen Meaning Bank](https://gmb.let.rug.nl) dataset in the root folder.

# Model Architecture
1. The Model that is used to build an NER model is a combination of a Bi-LSTM & CRF.\
2. The Model uses Bayesian Optimization to tune the parameters.\
3. Currently two different feature engineering methods are used:
  * Words
  * Words + POS Tags

# Future Scope
1. Use of Embeddings (Flair, Fast Text, Glove, Elmo, BERT)\
2. Deeper Networks
