# Task 3: Handwritten Character Recognition

## Objective
To develop a deep learning model using Convolutional Neural Networks (CNN) to recognize handwritten characters from image data.

## Approach
Image processing and deep learning techniques were applied. The MNIST dataset was used for training and testing the CNN model.

## Dataset
MNIST dataset containing:
- 60,000 training images
- 10,000 testing images
- 28x28 grayscale images
- 10 output classes (digits 0–9)

## Model Used
Convolutional Neural Network (CNN)

Architecture:
- Conv2D Layer (32 filters)
- MaxPooling
- Conv2D Layer (64 filters)
- MaxPooling
- Flatten
- Dense Layer (128 neurons)
- Output Layer (Softmax)

## Result
The model achieved high accuracy (~97–99%) on test data.

## Extension
This model can be extended to recognize full alphabets using EMNIST dataset or full words using CRNN.
