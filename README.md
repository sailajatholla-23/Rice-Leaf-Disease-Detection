# Rice Leaf Disease Detection Using Deep Learning

## Project Overview

Rice Leaf Disease Detection is a deep learning project designed to classify rice leaf images into different disease categories. The project uses Convolutional Neural Networks (CNN) and MobileNetV2 to identify diseases from leaf images and support early disease detection.

## Problem Statement

Rice plants can be affected by different leaf diseases that may impact crop health and productivity. Identifying diseases at an early stage can help farmers take appropriate action. This project explores image classification techniques to recognize common rice leaf diseases.

## Objectives

* Detect rice leaf diseases using image classification.
* Classify rice leaves into three disease categories.
* Train and evaluate deep learning models.
* Compare model performance to understand their effectiveness.

## Dataset Information

The dataset contains rice leaf images belonging to the following three classes:

1. **Bacterial Leaf Blight**
2. **Brown Spot**
3. **Leaf Smut**

The images are used to train and evaluate the disease classification models.

## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Jupyter Notebook
* Deep Learning
* Convolutional Neural Networks (CNN)
* MobileNetV2

## Models Used

### 1. Custom CNN

A Convolutional Neural Network is used to learn visual patterns from rice leaf images and classify them into disease categories.

### 2. MobileNetV2

MobileNetV2 is a lightweight deep learning architecture used for image classification. It can learn useful image features while keeping the model relatively efficient.

## Project Workflow

1. Load the rice leaf image dataset.
2. Explore the dataset and disease categories.
3. Preprocess the images for model training.
4. Split the dataset into training and testing sets, as implemented in the notebook.
5. Train the CNN and MobileNetV2 models.
6. Evaluate and compare model performance.
7. Review the classification results.

## Evaluation

The models are evaluated using the metrics implemented in the notebook. The evaluation results help compare their ability to classify rice leaf diseases.

## Challenges Faced

* Working with image data and preparing it for model training.
* Training deep learning models for multiple disease categories.
* Evaluating and comparing different model architectures.

## Project File

* `Rice Leaf Disease Detection.ipynb` — Contains the project workflow, implementation, model training, and evaluation.

## Conclusion

This project demonstrates how deep learning can be applied to rice leaf disease classification using image data. CNN and MobileNetV2 provide approaches for learning image features and predicting disease categories. The project provides practical experience in image preprocessing, model training, and evaluation.

## Future Improvements

* Train and evaluate the models on a larger and more diverse dataset.
* Improve classification performance through further experimentation.
* Develop a simple application that allows users to upload rice leaf images for prediction.
