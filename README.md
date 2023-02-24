# Word Embedding using Keras

This project is a deep learning model built using Keras to learn word embeddings from text data. Word embeddings are a popular way of representing words as vectors, 

which can then be used as input to machine learning models.

Dataset

The dataset used for this project is the IMDB movie review dataset, which contains 50,000 reviews split evenly into training and testing sets. Each review is labeled 

as either positive or negative.

Model

The model is built using Keras, a popular deep learning library. It consists of an input layer, an embedding layer, a flatten layer, and a dense output layer. The 

embedding layer learns the word embeddings from the input text data, while the dense output layer predicts the sentiment of the reviews.

Technologies Used

Python

Pandas Library

TensorFlow Library

Keras Library

Installation

pip install pandas
pip install tensorflow
pip install keras

Project Structure

├── Word-Embedding-using-Keras.ipynb

├── data

│   ├── imdb_test.csv

│   └── imdb_train.csv

└── README.md

Conclusion

This project demonstrates how to use Keras to learn word embeddings from text data. Word embeddings are a powerful way of representing words as vectors, which can be 

used as input to machine learning models. By using word embeddings, we were able to achieve high accuracy in predicting the sentiment of movie reviews. This model can 

be extended to other natural language processing tasks such as text classification, named entity recognition, and more.
