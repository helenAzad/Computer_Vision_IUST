
# Computer Vision Fundamentals Assignments

This repository contains a series of assignments for the **Basics of Computer Vision** course instructed by **Dr. Mohammadi**. Each assignment is organized in its own folder and covers various topics and practical exercises related to computer vision.

## Table of Contents

- [Introduction](#introduction)
- [Assignments](#assignments)
  - [Assignment 1](#assignment-1)
  - [Assignment 2](#assignment-2)
  - [Assignment 3](#assignment-3)
  - [Assignment 4](#assignment-4)
  - [Assignment 5](#assignment-5)
  - [Assignment 6](#assignment-6)
  - [Assignment 7](#assignment-7)
  - [Assignment 8](#assignment-8)
- [Installation](#installation)
- [Usage](#usage)
- [Contributors](#contributors)
- [License](#license)

## Introduction

This repository is a collection of assignments designed to provide hands-on experience with various computer vision techniques and algorithms. Each assignment folder contains the problem statements, required data, and solutions.

## Assignments

### Computer Vision Basics - Homework Series 1

**Topics Covered:**
- Grayscale Image Quantization
- Capturing clear images of moving objects
- Introduction to OpenCV

**Folder Contents:**
- `README.md`: Details of the assignment.
- `Basic.ipynb`
- `Numpy.ipynb`
- `Introduction_to_OpenCV.ipynb`

### Computer Vision Basics - Homework Series 2

**Topics Covered:**
- Histogram Analysis and Manipulation
- Histogram Matching
- Image Enhancement Techniques
- Noise Addition and Smoothing Filters
- Laplacian Operator
- Fourier Transform

**Folder Contents:**
- `README.md`: Details of the assignment.
- `Q1/Q1.ipynb`
- `Q2/Q2.ipynb`
- `Q3/Q3.ipynb`
- `Q4/Q4.ipynb`

### Computer Vision Basics - Homework Series 3

**Topics Covered:**
- Gradient and Edge Detection
- Fourier Transform
- Noise Removal using FFT
- Fourier Transform Applications
- RANSAC Algorithm for Circle Detection
- Hough Transform for Line Detection

**Folder Contents:**
- `README.md`: Details of the assignment.
- `Q2/Q2.ipynb`
- `Q3/Q3.ipynb`
- `Q5/Q5.ipynb`
- `Q7/Q7.ipynb`
- `Q8/Q8.ipynb`

### Computer Vision Basics - Homework Series 4

**Topics Covered:**
- Color Space Transformations
- Image Comparison
- Harris Corner Detection
- Affine Transformation
- Image Homography
- Camera Calibration

**Folder Contents:**
- `README.md`: Details of the assignment.
- `Q2/Q2.ipynb`
- `Q3/Q3.ipynb`
- `Q5/Q5.ipynb`
- `Q7/Q7.ipynb`
- `Q8/Q8.ipynb`

### Assignment 5

**Topics Covered:**
- Connected components labeling
- Region growing algorithm
- Otsu's thresholding
- Image morphology operations
- Hit-or-miss transform

**Folder Contents:**
- `README.md`: Details of the assignment.
- `q1`: Connected components labeling.
- `q2`: Region growing algorithm.
- `q3`: Otsu's thresholding on a 5x5 image.
- `q4`: Determining parameters for horizontal thresholding.
- `q5`: Morphological operations (erosion and dilation).
- `q6`: Effect of morphological operations.
- `q7`: Counting objects using morphology.
- `q8`: Skeleton extraction and reconstruction.
- `q9`: Boundary extraction using hit-or-miss transform.

### Assignment 6

**Topics Covered:**
- Convolutional Neural Networks (CNNs)
- Backpropagation
- Image Processing Techniques
- Practical Applications of CNNs

**Folder Contents:**
- `README.md`: Details of the assignment.
- `Exercise 1`: CNN Analysis.
- `Exercise 2`: Loss Function Optimization.
- `Exercise 3`: Inception Module.
- `Exercise 4`: Training and Batch Size Analysis.
- `Exercise 5`: LBP Coding.
- `Exercise 6`: Cats vs. Dogs CNN Training.
- `Exercise 7`: MNIST Classification using Hu Moments.

### Assignment 7

**Topics Covered:**
- Dilation and dilated convolution
- Comparison of convolutional layers
- Template matching

**Folder Contents:**
- `README.md`: Details of the assignment.
- `q1`: Analysis of dilated convolution.
- `q2`: Comparison of depthwise separable convolution and standard convolution.
- `q3`: Template matching and coin detection.
- `q4`: SAM model for segmentation.
- `q5`: Semantic segmentation with Unet.
- `q6`: Object detection with Fast R-CNN.

### Assignment 8

**Topics Covered:**
- Object detection using YOLO and SSD
- Focal Loss in RetinaNet
- Non-Maximum Suppression (NMS)
- YOLO bounding box conversion
- Training YOLO on custom datasets

**Folder Contents:**
- `README.md`: Details of the assignment.
- `q1`: CNN with sliding window vs. CNN without sliding window.
- `q2`: Comparison of YOLO and SSD.
- `q3`: Non-Maximum Suppression (NMS) necessity and implementation.
- `q4`: NMS with given bounding boxes.
- `q5`: YOLO bounding box conversion to pixel values.
- `q6`: Training YOLO on a custom dataset with live webcam evaluation.

## Installation

Clone the repository and install the required dependencies for each assignment:

```bash
git clone https://github.com/helenAzad/Computer_Vision_IUST.git
cd Computer_Vision_IUST
pip install -r requirements.txt
```

## Usage

Navigate to the assignment folder you want to work on and follow the instructions in the `README.md` file of that folder. For example:

```bash
cd assignment5/q1
jupyter notebook
```

## Contributors

- **Instructor:** Dr. Mohammadi
- **Teaching Assistants:**
  - Assignment 1: Morteza Haji Abadi
  - Assignment 2: Zahra Tabatabai, Saba Razi
  - Assignment 3: Aysa Miyaninia, Saba Razi, Zahra Tabatabai
  - Assignment 4: Zahra Tabatabai, Saba Razi, Poulaei, Hajiabadi, Zeinalabedin
  - Assignment 5: Pouya Elazar, Zain Alabedin
  - Assignment 6: Nadery Fard, Ghayouri, Mirakhourlou
  - Assignment 7: Nadery Fard, Ghayouri, Mirakhorloo
  - Assignment 8: Zamani, Azadi, Zare

## License

This project is licensed under the MIT License.
```

You can replace `helenAzad` with your actual GitHub username in the installation section. This update integrates the new assignment into the overall structure and ensures consistency across your `README.md` file.
