In this project, I created 4 classifiers for toxic tweet binary classification. These include a Logistic Regression model, a Latent Dirichlet Allocation (LDA) model, a Transformer deep learning model, and an LSTM deep learning model (that doesn't currently work with the dataset). These were implemented in Python using sklearn and pytorch. I preprocessed all the tweets and removed all unnecessary tokens, including any usernames and special characters. The models that worked were then trained and saved, so that they could be loaded to predict on a test dataset. The Logistic Regression and LDA used the whole training set, but gave weaker results, whereas I had to use less of the dataset for my Transformer as it was quite complex and would have took too long to train on my hardware at the time.

I have included the report for this project that details all my results.