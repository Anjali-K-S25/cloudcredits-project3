# Handwritten Digit Recognition using CNN (MNIST)

## Objective
To classify handwritten digits (0–9) using a Convolutional Neural Network.

## Dataset
MNIST Dataset (60,000 training images, 10,000 test images)

## Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn

## Steps
1. Load dataset
2. Normalize images
3. Build CNN model
4. Train model
5. Evaluate accuracy
6. Confusion matrix analysis

## Model Architecture
- Conv2D (32 filters)
- MaxPooling
- Conv2D (64 filters)
- MaxPooling
- Dense (128)
- Output (10 classes)

## Evaluation Metrics
- Accuracy
- Confusion Matrix
- Classification Report

## Result
Achieves ~98% accuracy on test data.

## How to Run
python main.py
