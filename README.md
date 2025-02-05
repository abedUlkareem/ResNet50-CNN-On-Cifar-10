# Project Description:

This project aims to compare the performance of two different models for image classification using the popular CIFAR-10 dataset. The performance of a traditional Convolutional Neural Network (CNN) is compared with the ResNet50 model, which relies on deep architecture with residual layers.

Project Steps:

Data Preparation: The CIFAR-10 dataset, which contains 60,000 images divided into 10 categories with 6,000 images per category, was loaded. The data was split into:

45,000 training images
10,000 testing images
5,000 validation images

Model Building:

CNN: A traditional convolutional neural network was built using several layers of convolutional layers, pooling layers, and fully connected layers.
ResNet50: The ResNet50 model, which incorporates residual layers, was used. These layers allow the model to skip some layers, improving training and reducing the risk of overfitting.
Training and Evaluation: Both models were trained on the training dataset and their performance was evaluated using the CIFAR-10 test dataset. Metrics such as classification accuracy were used to compare the performance of both models.

Results: The results were presented in a graph showing the classification accuracy of each model on the test data. Random images were also displayed along with the predicted and true labels to demonstrate the accuracy of each model.
