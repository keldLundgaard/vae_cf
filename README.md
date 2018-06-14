# Variational autoencoders for collaborative filtering

Notebook accompanies the paper "[Variational autoencoders for collaborative filtering](https://arxiv.org/abs/1802.05814)" by Dawen Liang, Rahul G. Krishnan, Matthew D. Hoffman, and Tony Jebara, in The Web Conference (aka WWW) 2018.

In this notebook, we show a complete self-contained example of training a variational autoencoder (as well as a denoising autoencoder) with multinomial likelihood (described in the paper) on the public Movielens-20M dataset, including both data preprocessing and model training.

The notebook has been updated slightly to work with newest version of Tensorflow and dependencies are better documented. 

## install dependencies
- CUDA-9.0 (unfortunately, always hard to do - atleast in this day an age)
- conda install -c anaconda tensorflow-gpu
- pip install -r requirements.txt