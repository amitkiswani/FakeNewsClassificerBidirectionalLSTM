# Fake News Classifier using Bidirectional LSTM


Python script for implementing a bidirectional LSTM (Long Short-Term Memory) neural network model to classify fake news. Here's a breakdown of what each part of the code does:

**Importing Libraries:** The code imports necessary libraries such as pandas for data manipulation, TensorFlow for deep learning, and NLTK for natural language processing tasks.

**Loading Dataset:** It loads the dataset from a CSV file using pandas. The dataset contains news headlines and their corresponding labels (whether the news is fake or real).

**Data Preprocessing:** The script performs preprocessing on the text data, including handling missing values, removing stopwords, and stemming.

**Text Encoding:** It encodes the preprocessed text data into numerical format using one-hot encoding.

**Embedding Representation:** The script converts the one-hot encoded sequences into dense vector representations using word embeddings.

**Model Building:** It defines a bidirectional LSTM neural network model using TensorFlow's Keras API. The model architecture consists of an embedding layer, a bidirectional LSTM layer, and a dense output layer with sigmoid activation for binary classification.

**Model Training:** The model is trained on the training data with binary cross-entropy loss and the Adam optimizer. Training is performed for a specified number of epochs.

**Model Evaluation:** After training, the model's performance is evaluated on the test data using accuracy as the metric. Additionally, it calculates the confusion matrix to assess the model's classification performance.

Overall, this script demonstrates how to build, train, and evaluate a bidirectional LSTM model for fake news classification using TensorFlow and Keras.
