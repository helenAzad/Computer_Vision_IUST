
# Computer Vision Fundamentals - Assignment 6

This repository contains solutions for the sixth series of assignments for the course **Fundamentals of Computer Vision** instructed by **Dr. Mohammad Reza Mohammadi**. The assignment focuses on Convolutional Neural Networks (CNNs), backpropagation, various image processing techniques, and applying these concepts to practical problems.

## Table of Contents

- [Introduction](#introduction)
- [Exercises](#exercises)
  - [Exercise 1: CNN Analysis](#exercise-1-cnn-analysis)
  - [Exercise 2: Loss Function Optimization](#exercise-2-loss-function-optimization)
  - [Exercise 3: Inception Module](#exercise-3-inception-module)
  - [Exercise 4: Training and Batch Size Analysis](#exercise-4-training-and-batch-size-analysis)
  - [Exercise 5: LBP Coding](#exercise-5-lbp-coding)
  - [Exercise 6: Cats vs. Dogs CNN Training](#exercise-6-cats-vs-dogs-cnn-training)
  - [Exercise 7: MNIST Classification using Hu Moments](#exercise-7-mnist-classification-using-hu-moments)
- [Installation](#installation)
- [Usage](#usage)
- [Contributors](#contributors)
- [License](#license)

## Introduction

This assignment covers various aspects of Convolutional Neural Networks (CNNs), including calculating output dimensions, number of parameters, and computational complexity. It also involves implementing region growing algorithms, analyzing loss functions, and using different training techniques to prevent overfitting.

## Exercises

### Exercise 1: CNN Analysis

1. Consider the following CNN architecture and answer the following questions (25 points):
   ```python
   Input(shape=(512, 512, 3))
   Conv2D(32, (9, 9), strides=2, padding='same', activation='relu')
   MaxPooling2D((4, 4), strides=4)
   Conv2D(64, (5, 5), strides=1)
   AveragePooling2D((2, 2), strides=2)
   Conv2D(128, (3, 3), strides=1, padding='valid', activation='relu')
   Conv2D(128, (3, 3), strides=1, padding='same', activation='relu')
   MaxPooling2D((2, 2), strides=2)
   Conv2D(512, (3, 3), strides=1, padding='valid', activation='relu')
   GlobalAveragePooling2D()
   Dense(1024)
   Dense(10)
   ```

   a) Calculate the output dimensions and the number of parameters for each layer.
   b) Compute the number of multiplications and additions in each layer.
   c) If `GlobalAveragePooling2D` is replaced with `Flatten`, how many times more parameters does the network have?

### Exercise 2: Loss Function Optimization

2. Given the loss function \( L = x^2 - 10x + e^{0.0001} \) with an initial value of \( x = 20 \):
   - If \( x \) is updated using the gradient descent algorithm with different learning rates, match each updated value of \( x \) with its respective curve on the graph and explain why.
     - \( x = 14 \)
     - \( x = 19.4 \)
     - \( x = 19.94 \)

### Exercise 3: Inception Module

3. For the given inception module:
   - If the input dimensions are (12, 12, 32) and the number of filters for \( 1 \times 1 \), \( 3 \times 3 \), and \( 5 \times 5 \) convolutions are 64, 32, and 128 respectively, find the output dimensions.
   - If the number of filters is changed to 256, calculate the new output dimensions.

### Exercise 4: Training and Batch Size Analysis

4. Answer the following questions (10 points):
   - If \( t \) is the number of training samples, \( e \) is the number of epochs, and \( b \) is the batch size, how many times are the network weights updated?
   - Analyze the provided graph and determine whether it corresponds to Batch Gradient Descent or Mini-batch Gradient Descent. Explain your reasoning.
   - Suggest an appropriate action for each of the following scenarios and justify your choice:
     1. Data augmentation
     2. Increasing network layers
     3. Reducing the number of input features

### Exercise 5: LBP Coding

5. Compute the LBP8,1 code for the non-zero pixels of the following image (15 points):
   ```
   0 0 0 0 0
   0 250 200 50 0
   0 180 100 80 0
   0 200 40 70 0
   0 0 0 0 0
   ```

   a) If all pixels are added with a constant \( C \), how does the code change? What if they are multiplied?

### Exercise 6: Cats vs. Dogs CNN Training

6. Refer to the `cats_vs_dogs` notebook and train a CNN on the Cats vs. Dogs dataset. Use any techniques taught in the course to avoid overfitting. Report the test accuracy and plot the `loss` and `accuracy` for both training and validation sets during training. (40 points)

### Exercise 7: MNIST Classification using Hu Moments

7. Classify handwritten digits (0, 1, and 2) from the MNIST dataset using Hu moments and a machine learning model:
   - Download the MNIST dataset.
   - Extract a subset containing only digits 0, 1, and 2.
   - Preprocess the images by normalizing pixel values and resizing them if necessary.
   - Compute Hu moments for each image.
   - Train a machine learning model for classification using the Hu moments.
   - Display some of the images along with their predicted labels. (20 points)

## Installation

Clone the repository and install the required dependencies:

```bash
git clone https://github.com/helenAzad/Computer_Vision_IUST/HW6.git
cd computer-vision-assignment6
```

## Usage

Run the Jupyter notebooks to execute the code for each exercise:

```bash
jupyter notebook
```

Navigate to the notebook you want to run and execute the cells to see the results.

## Contributors

- **Instructor:** Dr. Mohammad Reza Mohammadi
- **Teaching Assistants:** Nadery Fard, Ghayouri, Mirakhourlou

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```
