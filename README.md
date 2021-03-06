# CNN-Handwritten-Digit-Classifier

The classic handwritten digit classification problem, using the MNIST Database.

# Model Architecture

![alt text](https://www.researchgate.net/profile/Kofi_Appiah/publication/252028600/figure/fig2/AS:298067136925718@1448076151592/Some-samples-of-the-MNIST-database.png "MNIST Database")

Uses Convolutional Neural Network (CNN) implemented in Keras to classify handwritten digits into the 10 categories, using the MNIST database, which contains black and white, 28x28 images of handwritten digits. (27000 training samples, 2998 test samples)

The model achieved 98% accuracy within 5 epochs with Adadelta optimizer!

1.   Convolution Layer (4x4 kernel size, 32 total filters)

2.    Flatten Layer

3.    Dense Layer (100 nodes, rectified linear activation)

4.    Dense Output Layer (10 nodes, softmax activation)
