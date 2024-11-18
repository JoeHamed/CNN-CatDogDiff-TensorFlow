# Convolutional Neural Network for Cat vs Dog Classification
- This project demonstrates how to build and train a Convolutional Neural Network (CNN) using `TensorFlow` and `Keras` to classify images of cats and dogs.
- It covers data preprocessing, model building, training, and making predictions.
## Features
- Preprocessing of images with ImageDataGenerator.
- CNN model for binary classification.
- Predict whether an image is a cat or a dog.
## Dataset Structure
dataset/  
├── training_set/  
│   ├── cats/  
│   └── dogs/  
└── test_set/  
    ├── cats/  
    └── dogs/  
    
## Installation
### 1. Clone the repository:
- `git clone https://github.com/your-username/cnn-cat-dog-classification.git`
### 2. Install the required libraries:
- `pip install -r requirements.txt`
  
## Usage
### 1. Train the model:
- `python cnn_model.py`
### 2. Make a prediction:
- Place an image in the `single_prediction` folder and run the script.

## Results
- Training Accuracy: `~99%`
- Test Accuracy: `~85%`
