# Computer Vision Basics - Homework Series 3

This repository contains the solutions for the first series of assignments for the course "Fundamentals of Computer Vision" instructed by Dr. Mohammad Reza Mohammadi. The exercises involve various tasks related to image processing, gradient calculations, edge detection, Fourier transforms, and more using Python and OpenCV.

## Table of Contents

1. [Exercise 1: Gradient and Edge Detection](#exercise-1-gradient-and-edge-detection)
2. [Exercise 2: Fourier Transform](#exercise-2-fourier-transform)
3. [Exercise 3: Noise Removal using FFT](#exercise-3-noise-removal-using-fft)
4. [Exercise 4: Fourier Transform Applications](#exercise-4-fourier-transform-applications)
5. [Exercise 5: RANSAC Algorithm for Circle Detection](#exercise-5-ransac-algorithm-for-circle-detection)
6. [Exercise 6: Hough Transform for Line Detection](#exercise-6-hough-transform-for-line-detection)
7. [How to Run the Notebooks](#how-to-run-the-notebooks)

## Exercise 1: Gradient and Edge Detection

**Tasks**:
- Calculate the gradient vector \(\nabla I(x, y)\) for an image.
- Explain the usefulness of the gradient vector.
- Compute the magnitude and direction of the gradient on the image plane.
- Describe the use of the gradient vector in the Canny edge detector and its advantages.
- Explain why the Laplacian operator is not ideal for edge detection.

**Solution**:
- Implemented the gradient calculations and provided detailed explanations of their usefulness and applications in edge detection.

## Exercise 2: Fourier Transform

**Tasks**:
- Read `1.jpg` and `2.jpg` from the `Q2` folder.
- Compute and display the Fourier transform, amplitude, and phase of each image.
- Swap the phase and amplitude of the two images and display the inverse Fourier transform of the results.

**Solution**:
- Implemented Fourier transform calculations and visualizations.
- Swapped phase and amplitude and analyzed the results.

## Exercise 3: Noise Removal using FFT

**Tasks**:
- Read `saffron.jpg` and remove noise using FFT.
- Apply the Canny edge detector to the denoised image.
- Compute the gradient and use `arctan2` to find gradient directions.
- Bonus: Propose a method to separate the stem from the petals using gradient directions.

**Solution**:
- Implemented noise removal using FFT and edge detection.
- Calculated gradient directions and provided a method for separating image components.

## Exercise 4: Fourier Transform Applications

**Tasks**:
- Provide three examples of Fourier transform applications in computer vision.
- Calculate the value of \(F(0,0)\) for the Fourier transform \(F(u,v)\) of an image \(f(x,y)\).

**Solution**:
- Detailed examples and explanations of Fourier transform applications.
- Mathematical calculation of \(F(0,0)\).

## Exercise 5: RANSAC Algorithm for Circle Detection

**Task**:
- Calculate the number of iterations required to detect a circle with a 99% probability, knowing that only 40% of the edges belong to the circle.

**Solution**:
- Provided the mathematical solution for the number of iterations needed using the RANSAC algorithm.

## Exercise 6: Hough Transform for Line Detection

**Tasks**:
- Compare Hough and LSD algorithms for line detection.
- Detect and remove circles from `1.jpg` using `cv2.HoughCircles` and `cv2.circle`.
- Detect lines in the image using `cv2.HoughLinesP` and display them.

**Solution**:
- Compared Hough and LSD algorithms.
- Implemented circle detection and removal, followed by line detection and visualization.

## Bonus Exercises

**Tasks**:
- Use `findContours` and `approxPolyDP` to find corners in `7.jpg` and classify the shape.

**Solution**:
- Implemented shape detection and classification.

## How to Run the Notebooks

1. Clone the repository:
    ```sh
    git clone https://github.com/helenAzad/computer_Vision_IUST/HW3.git
    cd HW3
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
    - `Q2/Q2.ipynb`
    - `Q3/Q3.ipynb`
    - `Q5/Q5.ipynb`
    - `Q7/Q7.ipynb`
    - `Q8/Q8.ipynb`

---

**Instructor**: Dr. Mohammad Reza Mohammadi  
**Teaching Assistants**: Aysa Miyaninia, Saba Razi, Zahra Tabatabai

**Assignment Deadline**: 25/1/1403

---
