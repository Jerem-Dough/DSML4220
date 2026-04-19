# DSML 4220 - Deep Learning
This repository contains coursework completed for **DSML 4220: Deep Learning**, a course focused on building and evaluating deep learning models for NLP and computer vision tasks. Topics include text vectorization, MLPs, CNNs, RNNs, word embeddings, and hyperparameter tuning.

## Labs
This section contains deep learning labs completed throughout the course.

- **Lab 1: Working with Text Data (lab1_text_data.ipynb):**  
  Built a simple sentiment classifier on the Airline Tweets dataset. Covered NLP preprocessing including stemming, lemmatization, and text vectorization.

- **Lab 2: MLP for Classifying Yelp Reviews (lab2_yelp_reviews.ipynb):**  
  Built a PyTorch MLP for sentiment classification on 50,000+ Yelp reviews, with custom Vocabulary and Vectorizer classes for preprocessing.

- **Lab 3: CNN for Classifying Surnames (lab3_cnn_for_surnames.ipynb):**  
  Applied a CNN to predict the nationality of a surname across 18 classes using character-level tokenization, comparing performance against an MLP baseline.

- **Lab 4: Model Tuning with Weights & Biases (lab4_model_tuning_w_b.ipynb):**  
  Used W&B sweeps to systematically experiment with hyperparameters — optimizer type, learning rate, batch size, and dropout — on the surname classification task.

- **Lab 5: Implementing LeNet with MNIST (lab5_lenet_w_mnist.ipynb):**  
  Implemented the LeNet CNN from scratch in PyTorch on the MNIST dataset, using TensorBoard for experiment tracking and Captum for model interpretability.

- **Lab 6: Airline Tweets with Word Embeddings (lab6_airline_tweets_w_embeddings.ipynb):**  
  Compared one-hot encoded inputs vs. pretrained GloVe embeddings for tweet sentiment classification, analyzing embedding similarity and model size tradeoffs.

- **Lab 7: RNN for Classifying Surnames (lab7_rnn_for_surnames.ipynb):**  
  Applied an RNN to the surname nationality task, rounding out an architectural comparison across MLP, CNN, and RNN approaches on the same dataset.

- **Lab 8: Generating Surnames with a GRU RNN (lab8_rnn_surname_generation.ipynb):**  
  Trained a GRU-based RNN to generate novel surnames conditioned on nationality, shifting focus from classification to sequence generation.

Each lab is implemented in **Python** with **PyTorch**.
