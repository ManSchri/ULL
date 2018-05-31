The following files are included here:
* **Train_word2vec.ipynb** is used to train the Skip-gram model, it needs the file 'europarl-training.en' present in the same folder and gensim installed to run correctly.
* **gensim_skipgram_model** combined with both .npy files contain the trained model from Train_word2vec.ipynb
* **senteval_embedalign.ipynb** runs the senteval tests on the Embedalign model (paths to the SentEval folder might need changing and in senteval_skipgram.ipynb)
* **senteval_skipgram.ipynb** does the same with the Skip-gram model, this also needs gensim
