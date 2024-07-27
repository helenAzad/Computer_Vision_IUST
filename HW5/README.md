```
# Computer Vision Fundamentals - Assignment 5

This repository contains solutions for the fifth series of assignments for the course **Fundamentals of Computer Vision** instructed by **Dr. Mohammadi**. The assignment focuses on connected components, region growing, Otsu's thresholding, morphological operations, and image analysis techniques.

## Table of Contents

- [Introduction](#introduction)
- [Exercises](#exercises)
  - [Exercise 1: Connected Components](#exercise-1-connected-components)
  - [Exercise 2: Region Growing Algorithm](#exercise-2-region-growing-algorithm)
  - [Exercise 3: Otsu's Thresholding](#exercise-3-otsus-thresholding)
  - [Exercise 4: Horizontal Thresholding](#exercise-4-horizontal-thresholding)
  - [Exercise 5: Erosion and Dilation](#exercise-5-erosion-and-dilation)
  - [Exercise 6: Morphological Operations](#exercise-6-morphological-operations)
  - [Exercise 7: Car and Flower Counting](#exercise-7-car-and-flower-counting)
  - [Exercise 8: Morphological Skeleton](#exercise-8-morphological-skeleton)
  - [Exercise 9: Hit-or-Miss Operation](#exercise-9-hit-or-miss-operation)
- [Installation](#installation)
- [Usage](#usage)
- [Contributors](#contributors)
- [License](#license)

## Introduction

This assignment involves various image processing tasks such as finding connected components, implementing region growing algorithms, performing Otsu's thresholding, and applying morphological operations. It requires both theoretical understanding and practical implementation of these techniques.

## Exercises

### Exercise 1: Connected Components

1. Given image `q1`, find the connected components and label each component with a different color. Print the total number of components on the image. (5 points)

### Exercise 2: Region Growing Algorithm

2. Implement the region growing algorithm for image `q2`. Based on a seed point, color the person's face with your desired color. Implement both 4-connectivity and 8-connectivity, compare them, and test various thresholds. Do not use ready-made functions. (15 points)

### Exercise 3: Otsu's Thresholding

3. Generate a random 5x5 image (single channel with values in the range 1 to 15). Apply Otsu's algorithm for threshold levels 6 and 10 on paper. Determine which threshold level is better. (10 points)

### Exercise 4: Horizontal Thresholding

4. Sadegh has applied horizontal thresholding with five different combinations of arguments on an image from his book. Determine the values of `C`, `blockSize`, and `thresholdType` for each of the images `q4_1` to `q4_5` and explain your reasoning. Possible values are:
   - `C`: [5, 30]
   - `blockSize`: [21, 41]
   - `thresholdType`: [THRESH_BINARY, THRESH_BINARY_INV] (10 points)

### Exercise 5: Erosion and Dilation

5. Apply the erosion and dilation operations on the given image using the specified structuring element. Use reflect padding if needed, and place the anchor in the center of the structuring element. (10 points)

### Exercise 6: Morphological Operations

6. Analyze the effect of the following morphological operations on the given image and describe what processing is performed on the input image. (5 points)

### Exercise 7: Car and Flower Counting

7. Using morphological operations, write a program to count the number of cars in `car.jpg`. Convert the image to binary, remove extra lines using morphological operations, and find the number of cars using helper functions. (15 points)
   - Write a program to count the number of sunflowers in `flower.jpg`. Use the color image and focus on the circular part of the flower to count them. (10 bonus points)

### Exercise 8: Morphological Skeleton

8. a) Without using ready-made library functions, extract the skeleton of images `q8_5` to `q8_7` using morphological knowledge. (15 points)
   b) Reconstruct the original images from the skeleton by saving the steps of skeleton extraction. (10 points)

### Exercise 9: Hit-or-Miss Operation

9. Using the hit-or-miss operator, find the boundaries of the given image and determine the appropriate structuring elements. (5 points)

## Installation

Clone the repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/computer-vision-assignment5.git
cd computer-vision-assignment5
pip install -r requirements.txt
```

## Usage

Run the Jupyter notebooks to execute the code for each exercise:

```bash
jupyter notebook
```

Navigate to the notebook you want to run and execute the cells to see the results.

## Contributors

- **Instructor:** Dr. Mohammadi
- **Teaching Assistants:** Peyolaee Zare, Zeinolabedin

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

Feel free to customize the repository URL, add any additional sections if needed, and update any specific details related to your project.
