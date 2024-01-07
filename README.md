# Amazon Review Classification

## Project Overview
In this project I attempted to use neural networks to classify Amazon customer reviews into different classes based on their star rating, trying and comparing different embedding methods.

## Project Details
Initially I used tensorflow's inbuilt text vectorization to embed the reviews into mulit-hot vectors in a bag-of-words approach. Next I tried an n-gram approach testing different values of n. I got the best results with n=3.
Later I used pre-trained bert embeddings to vectorize my text. I tried this on the complete reviews and their summaries separately. I also attempted to visualize the embeddings in a scatter plot using sklearns TSNE.

The dataset I used is a collection of Amazon customer reviews and review summaries of products in their video game category. It can be found [here](https://nijianmo.github.io/amazon/index.html) 
