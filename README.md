# 📝 Toxic Tweet Classifiers

In this project, I created **4 classifiers** for **toxic tweet binary classification**. These include a **Logistic Regression** model, a **Latent Dirichlet Allocation (LDA)** model, a **Transformer** deep learning model, and an **LSTM** deep learning model (which currently does not work with the dataset). All models were implemented in **Python** using **scikit-learn** and **PyTorch**.

## ⚙️ Key Features

- **Data Preprocessing**: I preprocessed the tweets to remove unnecessary tokens, including usernames, special characters, and other irrelevant data points. This cleaning process was essential for improving model performance.
  
- **Logistic Regression & LDA**: These models were trained on the full training set. While they performed reasonably well, they yielded weaker results compared to the deep learning models.

- **Transformer Model**: This deep learning model used a smaller portion of the dataset for training due to hardware limitations. The Transformer showed better results compared to the classical models.

- **LSTM Model**: Though the LSTM model was also implemented, it did not currently work with the dataset, likely due to data preprocessing issues or the complexity of the model itself.

- **Model Saving**: The models that worked were trained, saved, and can be loaded to predict on a test dataset. This approach allows for easy model reuse and testing.

## 📊 Project Report

The project includes a detailed report that explains the methodology, model performance, and results of each approach, including comparisons between the models.
