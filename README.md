# MNIST-Digit-Recognition

I have recognized the handwritten digits from famous MNIST dataset using Convolutional Neural Network (CNN). 
I have augmented the image by shifting the image to 4 directions. 
I have used 2 Convolutional Layers with 64 filters of (3,3) shape and another 2 Convolutional Layers with 128 filters of the same shape. The padding is "Same" for all the layers. 
I have used Relu activation function for all the convolutional layers. 
I have used 4 Max Pooling Layers. 
I have used 2 Dropout layers with a rate of 0.5 to prevent overfitting. 
I have used Softmax for the final classification layer. 
I have set the epoch numbers to 15. 
