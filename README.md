# Plant Disease Classifier

This project demonstrates how to build a simple yet effective Convolutional Neural Network (CNN) to classify plant diseases from images using Keras and TensorFlow. The model is designed to identify three conditions in plants: Healthy, Rust, and Powdery mildew.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Web Application](#web-application)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The Plant Disease Classifier is a deep learning project aimed at detecting and classifying plant diseases from images. The model distinguishes between three classes:

- *Healthy*: Plants free from any diseases.
- *Rust*: Plant diseases caused by Pucciniales fungi, leading to severe deformities.
- *Powdery*: Plant diseases caused by Erysiphales fungi, which threaten agriculture and horticulture.

## Dataset

The dataset used for this project consists of 1,530 images labelled into three categories: Healthy, Rust, and Powdery. The images are divided into training, validation, and test sets.

<https://www.kaggle.com/datasets/rashikrahmanpritom/plant-disease-recognition-dataset>.

## Installation

To get started, clone this repository and install the required dependencies:

git clone <https://github.com/Akshaya-2003/Plant-Disease-Classifcation.git>

cd plant-disease-classifier

pip install -r requirements.txt

Ensure you have TensorFlow and Keras installed in your environment.

## Usage

### Running the Web Application

1. *Load the Pre-trained Model*: Ensure you have the pre-trained model file (plant_disease_classifier.keras) in the project directory.
2. *Start the Flask App*: Run the Flask application using the following command:

python app.py

1. *Upload and Predict*: Open your browser and navigate to <http://127.0.0.1:5000/>. Upload an image of a plant leaf to predict its condition (Healthy, Rust, or Powdery).

## Model Training

If you wish to train the model from scratch, follow these steps:

1. Prepare the dataset by organizing images into respective folders for training, validation, and testing.
2. Use a script or Jupyter notebook to define and train the CNN model using Keras.
3. Save the trained model to a file (plant_disease_classifier.keras).

## Web Application

The web application is built using Flask. It allows users to upload an image and get a prediction for the plant's condition. The application processes the image, prepares it for the model, and returns the classification result.

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or improvements, feel free to open an issue or create a pull request.
