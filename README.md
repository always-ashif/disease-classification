# Potato Disease Classification using CNN

A deep learning project that uses a Convolutional Neural Network (CNN) to classify potato leaf images into different disease categories.

## Classes

The model classifies potato leaves into 3 classes:

- Healthy
- Early Blight
- Late Blight

## Dataset

The dataset is hosted on Kaggle.

Dataset: https://www.kaggle.com/datasets/arjuntejaswi/plant-village

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib

## Model Architecture

The CNN model contains:

- Image Resizing and Rescaling
- Conv2D layers
- MaxPooling2D layers
- Flatten layer
- Dense layers
- Softmax output layer

## Data Preprocessing

The images are:

1. Resized to 256 × 256 pixels
2. Rescaled from 0–255 to 0–1
3. Augmented using:
   - Random Flip
   - Random Rotation

## Dataset Split

The dataset is divided into:

- 80% Training
- 10% Validation
- 10% Testing

## Model Training

The model uses:

- Optimizer: Adam
- Loss: Sparse Categorical Crossentropy
- Metric: Accuracy

## Results

Training Accuracy: 98.44%

Validation Accuracy: 95.83%

Test Accuracy: 95.31%

## Project Structure

```text
potato-disease-classification/
│
├── potato-disease-classification.ipynb
├── README.md
└── requirements.txt
