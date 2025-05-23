#Traffic-Sign-Classification

Traffic Sign Classification using Convolutional Neural Networks
This project demonstrates how to build, train, and evaluate a Convolutional Neural Network (CNN) for classifying traffic signs. The model is built using TensorFlow and Keras and is trained on the German Traffic Sign Recognition Benchmark (GTSRB) dataset. This type of model can be a fundamental component in applications like smarter cars and driver assistance systems.

Project Overview
The goal of this project is to accurately classify images of traffic signs into one of 43 different classes. The process involves:

Data Acquisition: Downloading the GTSRB dataset from Kaggle.
Data Preprocessing: Handling uneven image dimensions, resizing images to a consistent size (50x50 pixels), normalizing pixel values, and splitting the data into training and validation sets.
Model Building: Designing a CNN architecture using Keras Sequential API, including Convolutional layers, MaxPooling layers, Dropout layers, Flatten, and Dense layers.
Model Training: Compiling and training the CNN model on the preprocessed training data.
Model Evaluation: Making predictions on the test set and evaluating the model's performance.
Dataset
The German Traffic Sign Recognition Benchmark (GTSRB) dataset contains over 50,000 images of traffic signs belonging to 43 classes. The dataset is split into a training set and a test set.
