# Geometric Shape Recognition

Machine learning project comparing traditional feature extraction with Random Forest and CNN approaches for classifying hand-drawn geometric shapes. Achieves 99.4% accuracy with CNN implementation.

## Project Description

This project implements two machine learning approaches for recognizing hand-drawn geometric shapes. The system classifies images into eight geometric categories using both traditional feature extraction with Random Forest and modern convolutional neural networks. The CNN approach significantly outperformed with 99.42% accuracy compared to 75% for the Random Forest method.

## Dataset

The dataset contains 12,000 images of eight geometric shapes from Kaggle. All images are grayscale, 64×64 pixels, and organized into train/val/test directories.

## Implementation

### Approach 1: Random Forest
- Manual feature extraction (area, perimeter, circularity, etc.)
- Data augmentation techniques
- Custom cost matrix for error weighting
- 75% weighted accuracy

### Approach 2: CNN
- Two convolutional layers with ReLU activation
- Max pooling and dropout layers
- 15 epochs training
- 99.42% weighted accuracy

## Files
- `Arbre_de_décision.ipynb` - Random Forest implementation
- `CNN.ipynb` - CNN implementation
- Dataset: https://www.kaggle.com/datasets/reevald/geometric-shapes-mathematics/data

## Requirements
Python 3.7+, OpenCV, scikit-learn, TensorFlow/Keras, NumPy, Matplotlib
