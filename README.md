# Spider Species Recognition Using CNN

## Overview

This project is a deep learning-based image classification system that identifies different spider species from images using Convolutional Neural Networks (CNN) and VGG16 Transfer Learning.

The model extracts image features using a pre-trained VGG16 network and classifies spider species into predefined categories.

## Features

* Spider species image classification
* Transfer Learning using VGG16
* Feature extraction using bottleneck features
* TensorFlow and Keras implementation
* Softmax-based multi-class prediction
* Model evaluation with accuracy metrics

## Dataset

The dataset contains images of the following spider species:

* Blue Tarantula
* Ladybird Mimic Spider
* Peacock Spider

Directory Structure:

Dataset/
├── train/
│ ├── Blue Tarantula/
│ ├── Ladybird Mimic Spider/
│ └── Peacock Spider/
│
├── test/
│ ├── Blue Tarantula/
│ ├── Ladybird Mimic Spider/
│ └── Peacock Spider/

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Pandas
* Scikit-Learn
* OpenCV
* VGG16 Transfer Learning

## Model Architecture

1. Image Preprocessing
2. Feature Extraction using VGG16
3. Flatten Layer
4. Dense Layer (100 Units)
5. Dropout Layer (0.5)
6. Dense Layer (50 Units)
7. Dropout Layer (0.3)
8. Output Layer (Softmax)

## Installation

Clone the repository:

git clone https://github.com/yourusername/Spider-Species-Recognition-CNN.git

Navigate to the project folder:

cd Spider-Species-Recognition-CNN

Install dependencies:

pip install -r requirements.txt

## Running the Project

Train the model:

python train.py

Test the model:

python predict.py

## Example Prediction

Input Image:
Blue Tarantula

Output:

Label: Blue Tarantula ---> 98.45%
Label: Ladybird Mimic Spider ---> 83.59%
Label: Peacock Spider ---> 72.33%

Predicted Class:
Blue Tarantula

## Results

The model successfully classifies spider species using transfer learning and achieves high classification accuracy on the test dataset.

## Future Improvements

* Add more spider species
* Use data augmentation
* Deploy using Flask or FastAPI
* Create a web application interface
* Improve model accuracy with EfficientNet or ResNet

## Author

Bipin Yadav
