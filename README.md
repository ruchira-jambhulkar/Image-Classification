# Image-Classification

Title: Image Classification with MNIST dataset using CNN

Dataset:

The MNIST dataset is a commonly used dataset for image classification. The tensorflow and keras API allows easy import of MNIST data. It contains 60,000 training images and 10,000 testing images. The x_train and x_test contain greyscale RGB codes from 0 to 255, and y_train, y_test contain labels from 0 to 9 represents which number they actually are.

Reshaping and Normalizing the images:

The image in a MNIST dataset is a 3 dimensional. The Keras API requires 4 dimensional numpy array. To achieve the 4 dimensional numpy array, the data is normalized by dividing the RGB codes to 255.

Building the CNN model:

The model is created by using high level Keras API with tensorflow at the backend. The sequential model is created by adding layers Conv2D, MaxPooling, Flatten, Dense, Dropout.

Compiling and Fitting the model:

Optimizer: adam
loss function: sparse_categorical_crossentropy
metrics: accuracy
epochs: 10

Evaluating the model:

The 98.5% accuracy is obtained with 0.06 loss value.
