# Image Classification Project for Emotion Detection

## Overview
This project develops a deep learning model to classify images of faces based on emotional expressions, specifically distinguishing between 'Happy' and 'Sad' emotions. The project utilizes TensorFlow and Keras for building and training a convolutional neural network (CNN), OpenCV for image preprocessing, and Matplotlib for visualizations.

## Technology Stack
- **Python**: Primary programming language.
- **TensorFlow/Keras**: Frameworks used for model creation, training, and evaluation.
- **OpenCV**: For handling image file operations.
- **Matplotlib**: For plotting training and validation results, and displaying images.

## Project Structure
/ImageClassification
|-- data/
|   |-- happy/
|   |-- sad/
|-- models/
|   |-- imageclassifier.h5
|-- logs/
|-- ImageClassification.ipynb
|-- requirements.txt
|-- README.md

## Setup
1. **Install Python**: Ensure Python is installed on your system.
2. **Clone the Repository**: Clone this repository to your local machine.
3. **Install Dependencies**: Install the necessary Python packages using:


## Running the Project
1. **Prepare the Data**: Organize your images in the `data/` directory under `happy` and `sad` subdirectories.
2. **Train the Model**: Open and run the Jupyter Notebook `ImageClassification.ipynb` to train the model. This notebook contains steps for data preprocessing, model training, and evaluation.
3. **Model Evaluation**: After training, the model's performance can be evaluated on a test set within the notebook.
4. **Making Predictions**: Use the trained model to make predictions on new data. Code for making predictions is also provided in the notebook.
5. **Visualize Results**: The training and validation accuracy and loss graphs are plotted in the notebook.

## Features
- **Image Preprocessing**: Images are preprocessed and normalized to fit the model's input requirements.
- **Model Architecture**: The CNN is built with several convolutional and pooling layers, followed by dense layers for classification.
- **Training Visualizations**: Training progress is visualized in real-time to monitor accuracy and loss metrics.
- **Model Evaluation**: Precision, recall, and accuracy metrics are used to evaluate the model's performance.
- **Predictions**: The model can classify new images into 'happy' or 'sad' categories.
