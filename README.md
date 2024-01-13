## Spam-Detection-for-Text-Messages

- This project draws inspiration from a [FreeCodeCamp course](https://www.freecodecamp.org/learn/machine-learning-with-python/machine-learning-with-python-projects/neural-network-sms-text-classifier). We built a simple Recurrent Neural Network to perform spam detection on text messages.
- Initially, Pandas was used to retrieve features and labels  of both training and testing data. Each text sequence was tokenized and padded.
- Our simple sequence model has an embedding layer that outputs a 100-dimensional word embedding, an LSTM layer with 50 units, a `GlobalMaxPooling1D` layer followed by an output layer with sigmoid activation.
- With merely 5 epochs of training, we achieved a test accuracy of **98.99%**.
