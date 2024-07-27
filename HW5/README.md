
```markdown
# Computer Vision Homework Series 5

Welcome to the repository for the fifth series of assignments for the course **Fundamentals of Computer Vision**, instructed by **Dr. Mohammad Reza Mohammadi**. This series focuses on connected components, region growing, Otsu's thresholding, morphological operations, and object counting using Python and image processing libraries.

## Table of Contents

- [Introduction](#introduction)
- [Exercises](#exercises)
  - [Exercise 1: Connected Components](#exercise-1-connected-components)
  - [Exercise 2: Region Growing Algorithm](#exercise-2-region-growing-algorithm)
  - [Exercise 3: Otsu's Thresholding](#exercise-3-otsus-thresholding)
  - [Exercise 4: Adaptive Thresholding](#exercise-4-adaptive-thresholding)
  - [Exercise 5: Erosion and Dilation](#exercise-5-erosion-and-dilation)
  - [Exercise 6: Morphological Processing](#exercise-6-morphological-processing)
  - [Exercise 7: Car and Flower Counting](#exercise-7-car-and-flower-counting)
  - [Exercise 8: Skeleton Extraction](#exercise-8-skeleton-extraction)
  - [Exercise 9: Hit-or-Miss Transformation](#exercise-9-hit-or-miss-transformation)
- [Installation](#installation)
- [Usage](#usage)
- [Contributors](#contributors)
- [License](#license)

## Introduction

This repository contains the solutions for the fifth series of homework assignments in the **Fundamentals of Computer Vision** course. The assignments cover various topics, including connected components, region growing, Otsu's thresholding, morphological operations, and object counting.

## Exercises

### Exercise 1: Connected Components

1. Identify the connected components in the given image `q1` and label each component with a different color. Also, print the total number of components on the image. (Use of ready-made functions is allowed) (Practical - 5 points)

### Exercise 2: Region Growing Algorithm

2. Implement the region growing algorithm for the given image `q2`. Color the face of the person based on the seed point with your desired color. Implement both 4-connectivity and 8-connectivity and compare the results. Test different thresholds and document the various results in your report. (Do not use ready-made functions) (Practical - 15 points)

### Exercise 3: Otsu's Thresholding

3. Generate a random 5x5 image (single channel with values ranging from 1 to 15). Then manually apply Otsu's algorithm for threshold levels 6 and 10 on paper. Determine the better threshold level. (Theoretical - 10 points)

### Exercise 4: Adaptive Thresholding

4. Sadegh recently applied adaptive thresholding with five different argument combinations on the image of his book, but now he doesn't know which resulting image corresponds to which combination of arguments. Refer to the images `[q4_1]` to `[q4_5]` and determine the values of `C`, `blockSize`, and `thresholdType` for each image. Explain your reasoning. (Theoretical - 10 points)
   - Possible parameter values:
     - `C`: [5, 30]
     - `blockSize`: [21, 41]
     - `thresholdType`: [THRESH_BINARY, THRESH_BINARY_INV]

### Exercise 5: Erosion and Dilation

5. Apply the given structural element to perform erosion and dilation on the provided image. Use reflect padding if necessary, and ensure the anchor is at the center of the structural element. (Theoretical - 10 points)

### Exercise 6: Morphological Processing

6. What will be the result of the morphological operation shown below on the given image? Describe the processing performed on the input image. (Theoretical - 5 points)

### Exercise 7: Car and Flower Counting

7. Using morphological techniques and the provided links:
   - Write a program to count the number of cars in the image `car.jpg`. (Practical - 15 points)
     - Hint: Convert the image to a binary image, remove extra lines using morphological operators, and find the cars using auxiliary functions.
   - Write a program to count the number of sunflowers in the image `flower.jpg` using the color image. Focous on the circular part of the flower to find the number of flowers. (Practical - Bonus - 10 points)

### Exercise 8: Skeleton Extraction

8. Extract the skeletons of the images `[q8_5]` to `[q8_7]` without using ready-made library functions. (Practical - 15 points)
   - Save the steps of skeleton extraction and reconstruct the original images from the skeletons. (Practical - 10 points)

### Exercise 9: Hit-or-Miss Transformation

9. Use the hit-or-miss operator to find the boundaries of the given image and determine the appropriate structuring elements. (Theoretical - 5 points)

## Installation

To set up the project, clone the repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/computer-vision-homework.git
cd computer-vision-homework
pip install -r requirements.txt
```

## Usage

Run the Jupyter notebooks to execute the code for each exercise:

```bash
jupyter notebook
```

Navigate to the notebook you want to run and execute the cells to see the results.

## Contributors

- **Instructor:** Dr. Mohammad Reza Mohammadi
- **Teaching Assistants:** Zahra Tabatabaei, Saba Razi, Poulaei, Zeinalabedin

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

Feel free to replace the placeholders (like `https://github.com/yourusername/computer-vision-homework.git`) with your actual repository details. This README provides a clear overview of the project, its structure, and how to set it up and use it.

## Usage

Run the Jupyter notebooks to execute the code for each exercise:

```bash
jupyter notebook
```

Navigate to the notebook you want to run and execute the cells to see the results.

## Contributors

- **Instructor:** Dr. Mohammad Reza Mohammadi
- **Teaching Assistants:** Zahra Tabatabaei, Saba Razi, Poulaei, Zeinalabedin

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

Feel free to replace the placeholders (like `https://github.com/helenAzad/Computer_Vision_IUST.git`) with your actual repository details. This README provides a clear overview of the project, its structure, and how to set it up and use it.
