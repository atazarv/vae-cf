# Variational autoencoders for collaborative filtering

This notebook is a modified version of the notebook that accompanies the paper "[Variational autoencoders for collaborative filtering](https://arxiv.org/abs/1802.05814)" by Dawen Liang, Rahul G. Krishnan, Matthew D. Hoffman, and Tony Jebara, in The Web Conference (aka WWW) 2018.


We modified the original code to adjust, clean and preprocess a new publicly available dataset "[Yahoo! Music user ratings of musical artists, version 1.0](https://webscope.sandbox.yahoo.com/catalog.php?datatype=r&did=1)", then trained the model and fined-tuned the hyperparameters on the new dataset. 

In this notebook, we show a complete self-contained example of training a variational autoencoder (as well as a denoising autoencoder) with multinomial likelihood (described in the original paper).

This was done as the course project for the course "[Deep Generative Models, Computer Science, UC Irvine, Spring 2019]".
