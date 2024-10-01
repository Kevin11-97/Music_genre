# Music_genre
Music Genre Classification by extracting features and building model using Neural Network in Keras.

Features Extracted:
Chroma STFT, RMSE, Spectral Centroid, Spectral Bandwidth, Rolloff, Zero-Crossing Rate, MFCC
The Extracted Features are written in a csv file (data.csv)

The model is a neural network with three dense layers.
Uses ReLU activation in hidden layers and softmax for multi-class classification.
The model is compiled using the Adam optimizer with a learning rate of 0.001, categorical crossentropy as the loss function for multi-class classification, and accuracy as the metric.

Early stopping is used to prevent overfitting.


For Evaluation - Accuracy vs Loss plots are generated.


The trained model is then loaded, and it predicts the genre of a random audio file from the dataset.
