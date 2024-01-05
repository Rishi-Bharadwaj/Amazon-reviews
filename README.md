Amazon Review Classification

In this project I attempted to use neural networks to classify Amazon customer reviews into different classes based on their star rating. 
Initially i used tensorflow's inbuilt text vectorization to embed the reviews, following an ngram approach and trying different values of n.(I finally settled on n=3).
Later I used pre-trained bert embeddings to vectorize my text. I tried this on the complete reviews and their summaries separately. I also attempted to visualize the embeddings in a scatter plot using sklearns TSNE.
