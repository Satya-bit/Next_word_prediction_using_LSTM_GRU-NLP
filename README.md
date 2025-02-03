# Next_word_prediction_using_LSTM_GRU-NLP-
This project aims to detect the next word from the hamlet using LSTM and GRU RNN.

# Model Architecture

The model is built using TensorFlow and Keras, utilizing an embedding layer, stacked LSTM layers, and a dense output layer with a softmax activation function.

# Model Structure

Embedding Layer: Maps each input word to a dense vector representation of fixed size (100 dimensions).

LSTM Layer 1: Consists of 150 LSTM units with return_sequences=True, ensuring that the entire sequence is passed to the next LSTM layer.

Dropout Layer: Reduces overfitting by randomly setting 20% of activations to zero.

LSTM Layer 2: Contains 100 LSTM units that process the sequence further.

Dense Output Layer: Uses a softmax activation function to predict the next word among total_words possible outputs.

# Model Compilation

The model is compiled using:

Loss Function: Categorical cross-entropy, since the output is one-hot encoded.

Optimizer: Adam optimizer for adaptive learning rate adjustments.

Metric: Accuracy to track model performance.

STREAMLIT WAS USED FOR MAKING THE APP.
