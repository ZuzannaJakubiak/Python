# ANN - Cat or Dog?

This repository implements a Convolutional Neural Network (CNN) to classify images of dogs and cats. The model is designed to predict whether an image contains a dog or a cat, utilizing a binary classification approach based on image data.

### Introduction

The primary goal of this project is to construct a CNN that can accurately classify images of dogs and cats. The model will process images of varying sizes, resize them to a standard dimension, and then train using labeled datasets. 

### Key Components

1. **Data Preparation**: 
   - Images are resized to a consistent size of 150x150 pixels to standardize input data.
   - The dataset is split into training (90%) and validation (10%) subsets to evaluate model performance.

2. **Model Architecture**: 
   - The CNN consists of several convolutional layers followed by activation functions (ReLU) and max pooling layers to extract features from the images.
   - A flattening layer is used to convert the 2D feature maps into 1D vectors, followed by dense layers that lead to the final output layer. The output layer has a single neuron with a sigmoid activation function to classify the images as either a dog (1) or a cat (0).

3. **Model Training**: 
   - The model is compiled with binary cross-entropy as the loss function and RMSprop as the optimizer. Accuracy is monitored as an additional metric.
   - Training is performed for 10 epochs, and the best model weights are saved based on validation accuracy.

4. **Model Evaluation**: 
   - After training, the model is evaluated on both the training and validation sets to assess its performance. Predictions are made on a test dataset, classifying images based on a threshold of 0.5.

5. **Results Visualization**: 
   - Training accuracy and loss are plotted to visualize the model's learning progress over epochs. These plots help in understanding the model's performance and potential overfitting.

### Conclusions

1. **Model Accuracy**: The CNN model demonstrates effective classification of images, achieving good accuracy on both training and validation datasets.

2. **Feature Learning**: The convolutional layers successfully learn important features that differentiate between images of dogs and cats, showcasing the power of deep learning in image classification tasks.

3. **Validation Performance**: Continuous monitoring of validation accuracy during training helps ensure that the model generalizes well to unseen data.

4. **Opportunities for Improvement**: Future work could include experimenting with different architectures, regularization techniques, or data augmentation methods to further enhance model performance.
