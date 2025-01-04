# Natural Language Processing (Neural Methods) Tutorials

This repository consists of Python (PyTorch) examples to learn fundamental neural methods for Natural Language Processing (NLP).<br>
Each notebook has end-to-end implementation (for each task) from scratch, and describes fundamental ideas and background for each architecture.

1. [Primitive Embeddings (Sparse Vector)](./01_sparse_vector.ipynb)
2. [Custom Embedding (Dense Vector)](./02_custom_embedding.ipynb)
3. [Word2Vec algorithm (Negative Sampling)](./03_word2vec.ipynb)
4. [N-Gram detection with 1D Convolution](./04_ngram_cnn.ipynb)
5. [Neural Language Model - Basic FFN](./05_language_model_basic.ipynb)
6. [Neural Language Model - RNN (Recurrent Neural Network)](./06_language_model_rnn.ipynb)
7. [Encoder-Decoder Architecture (Seq2Seq)](./07_encoder_decoder.ipynb)
8. [Attention](./08_attention.ipynb)
9. [Transformer](./09_transformer.ipynb)

> I recommend you to run these examples on GPU-utilized machine.

Tutorials follow the history of NLP neural methods.<br>
In the latter part (from tutorial 5), I then focus on language models, improving the models by step-by-step approaches, and finally discuss how and why the widely used Transformer architecture matters.

NLP (natural language processing) has a long history in artificial intelligence, and generative models were also developed with traditional statistical models in 1950s - such as, [Hidden Markov Models (HMMs)](https://github.com/tsmatz/hmm-lds-em-algorithm) or [Gaussian Mixture Models (GMMs)](https://github.com/tsmatz/gmm).<br>
However, this repository focuses on recent neural methods examined in today's NLP.

> [Feb 2023] All examples were transformed (from TensorFlow) into PyTorch.

*Tsuyoshi Matsuzaki @ Microsoft*
