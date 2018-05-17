
# Learning Word Representations

This repository holds implementations and evaluations of three word embedding models: Skip-gram, Bayesian Skip-gram and EmbedAlign. 

To run any of the models go to the respective notebook Skipgram.ipynb, BayesianSkipgram.ipynb and EmbedAlign.ipynb. The training data should be within the same folder for hansards and europarl dataset. 

To evaluate, having the Lexical Substitution Task dataset in the folder, run the respective Skipgram_evaluation.ipynb, BayesianSkipgram_evaluation.ipynb and EmbedAlign_evaluation.ipynb. 


All the rest of the files can be generated from code, although it may be helpful to load pre-generated wocabulary indices. 

## References

- Embedding Words as Distributions with a Bayesian Skip-gram Model (2017) - Brazinskas et al.  <a href="https://arxiv.org/abs/1711.11027">[pdf]</a>

- Deep Generative Model for Joint Alignment and Word Representation (2018) - Rios et al.  <a href="https://arxiv.org/abs/1802.05883">[pdf]</a>

- Efficient Estimation of Word Representations in Vector Space (2013) - Mikolov et al.  <a href="https://arxiv.org/abs/1301.3781">[pdf]</a>

- word2vec explained: Deriving mikolov et al.'s negative-sampling word-embedding method (2014) Goldberg et al.  <a href="https://arxiv.org/abs/1402.3722">[pdf]</a>



