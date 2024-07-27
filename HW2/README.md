# Computer Vision Basics - Homework Series 2

This repository contains the solutions for the second series of assignments for the course "Fundamentals of Computer Vision" instructed by Dr. Mohammad Reza Mohammadi. The exercises involve various tasks related to image processing, histogram manipulation, and filtering using Python and OpenCV.

## Table of Contents

1. [Exercise 1: Histogram Analysis and Manipulation](#exercise-1-histogram-analysis-and-manipulation)
2. [Exercise 2: Histogram Matching](#exercise-2-histogram-matching)
3. [Exercise 3: Image Enhancement Techniques](#exercise-3-image-enhancement-techniques)
4. [Exercise 4: Noise Addition and Smoothing Filters](#exercise-4-noise-addition-and-smoothing-filters)
5. [Exercise 5: Laplacian Operator](#exercise-5-laplacian-operator)
6. [Exercise 6: Fourier Transform](#exercise-6-fourier-transform)
7. [How to Run the Notebooks](#how-to-run-the-notebooks)

## Exercise 1: Histogram Analysis and Manipulation

**Tasks**:
- Compute and plot the histogram of a given image.
- Apply histogram stretching and clipping to the image, plot the resulting image and its histogram.

**Solution**:
- Implemented functions to calculate and plot histograms.
- Applied histogram stretching and clipping based on custom-defined ranges for optimal results.

## Exercise 2: Histogram Matching

**Tasks**:
- Perform histogram matching on two given images.
- Implement the required functions in `Q2` notebook without using libraries other than `numpy`.

**Solution**:
- Implemented histogram matching algorithm.
- Provided analysis and comparisons of the results.

## Exercise 3: Image Enhancement Techniques

**Tasks**:
- Implement global histogram equalization using OpenCV.
- Implement and compare local enhancement methods ACE and CLAHE.
- Analyze the advantages and disadvantages of each method.

**Solution**:
- Implemented and analyzed global histogram equalization.
- Completed ACE and CLAHE implementations and provided detailed comparisons.

## Exercise 4: Noise Addition and Smoothing Filters

**Tasks**:
- Implement a function to add salt-and-pepper noise to an image.
- Complete smoothing filter functions (mean, median, Gaussian) and analyze the effects of kernel size.
- Compare custom filter implementations with OpenCV's built-in functions.

**Solution**:
- Added salt-and-pepper noise to an image and implemented smoothing filters.
- Analyzed and compared the performance and results of different filters.

## Exercise 5: Laplacian Operator

**Task**:
- Calculate and apply the Laplacian operator to a given image.

**Solution**:
- Implemented the Laplacian operator and analyzed the result on the provided image.

## Exercise 6: Fourier Transform

**Task**:
- Calculate the Fourier transform of a 2x2 image.

**Solution**:
- Computed the Fourier transform and provided detailed calculations and analysis.

## How to Run the Notebooks

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/computer-vision-basics-hw2.git
    cd computer-vision-basics-hw2
    ```

2. Set up a virtual environment (optional but recommended):
    ```sh
    python -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

3. Install the required packages:

4. Run Jupyter Notebook:
    ```sh
    jupyter notebook
    ```

5. Open and run the provided notebooks:
    - `Q1/Q1.ipynb`
    - `Q2/Q2.ipynb`
    - `Q3/Q3.ipynb`
    - `Q4/Q4.ipynb`

## Notebooks Overview

### Q1.ipynb

This notebook covers histogram calculation, stretching, and clipping. Ensure you complete the functions and visualize the results as specified in the assignment.

### Q2.ipynb

This notebook focuses on histogram matching without using external libraries other than `numpy`. Complete the required sections and analyze the output.

### Q3.ipynb

This notebook involves implementing and analyzing both global and local image enhancement techniques. Make sure to complete the functions for ACE and CLAHE and provide a detailed analysis.

### Q4.ipynb

This notebook involves adding noise to images and applying various smoothing filters. Implement the specified filters and compare your results with OpenCV's built-in functions.

---

**Instructor**: Dr. Mohammad Reza Mohammadi  
**Teaching Assistants**: Zahra Tabatabai, Saba Razi

**Assignment Deadline**: 26/12/1402

---
