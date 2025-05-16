# Handwritten Digit Recognition with TensorFlow

## Project Overview
This project implements a Convolutional Neural Network (CNN) for recognizing handwritten digits (0-9) using the MNIST dataset. The model achieves ~99% accuracy in classifying digits from images.

## Features
- Handwritten digit classification (0-9)
- Image preprocessing and visualization
- CNN model built with TensorFlow/Keras
- Model evaluation and testing
- Support for custom image input via PIL

## Tech Stack
- **TensorFlow/Keras** - For building and training the CNN model
- **NumPy** - For numerical operations and data preprocessing
- **Matplotlib** - For data visualization and plotting
- **PIL (Python Imaging Library)** - For handling image inputs

## Requirements
- Python 3.6+
- TensorFlow 2.x
- NumPy
- Matplotlib
- Pillow (PIL)

Install requirements:
```bash
pip install tensorflow numpy matplotlib pillow
```

## Dataset
The model uses the standard MNIST dataset containing 60,000 training and 10,000 test images of handwritten digits (28x28 pixels grayscale).

## Model Architecture
The CNN consists of:
- 2 Convolutional layers with ReLU activation
- MaxPooling layers
- Dropout layer for regularization
- Dense layers for classification

## Results
- Training accuracy: ~99.5%
- Test accuracy: ~99.0%

## Model 
- Model is saved with the name model.keras

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
