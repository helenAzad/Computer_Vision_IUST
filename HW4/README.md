# Computer Vision Homework Series 4

Welcome to the repository for the fourth series of assignments for the course **Fundamentals of Computer Vision**, instructed by **Dr. Mohammad Reza Mohammadi**. This series focuses on color space transformations, gradient calculations, edge detection, Fourier transforms, homography, and camera calibration.

## Table of Contents

- [Introduction](#introduction)
- [Exercises](#exercises)
  - [Exercise 1: Color Space Transformations](#exercise-1-color-space-transformations)
  - [Exercise 2: Image Comparison](#exercise-2-image-comparison)
  - [Exercise 3: Harris Corner Detection](#exercise-3-harris-corner-detection)
  - [Exercise 4: Affine Transformation](#exercise-4-affine-transformation)
  - [Exercise 5: Image Homography](#exercise-5-image-homography)
  - [Exercise 6: Camera Calibration](#exercise-6-camera-calibration)
- [Installation](#installation)
- [Usage](#usage)
- [Contributors](#helenAzad)

## Introduction

This repository contains the solutions for the fourth series of homework assignments in the **Fundamentals of Computer Vision** course. The assignments cover various topics, including color space transformations, image comparison, Harris corner detection, affine transformations, homography, and camera calibration.

## Exercises

### Exercise 1: Color Space Transformations

1. Implement functions to perform the following transformations on `image1.jpg`:
   - RGB to CMYK and vice versa (note: RGB scale is 255, CMYK scale is percentage)
   - RGB to HSI

### Exercise 2: Image Comparison

2. Implement a function to compare two images, `image2.jpg` and `image3.jpg`, and identify the differences between them using a method similar to what was taught in class.

### Exercise 3: Harris Corner Detection

3. Compute the horizontal and vertical derivatives of an image:
   - Compute the Harris matrix with a 3x3 window for a specified region.
   - Calculate \( R = \text{det}(M) - k \cdot \text{trace}^2(M) \) for the specified region (set \( k \) to 0.04).
   - Determine if the specified region is an edge, corner, or flat area, and explain why.

### Exercise 4: Affine Transformation

4. Compute the affine transformation for the following tasks:
   - Calculate the transformation relationship.
   - Determine the coordinates of points 'C' and 'E' after transformation.

### Exercise 5: Image Homography

5. Find the homography transformation \( H \) that converts each set of lines:
   - Convert lines \(\{x + 5 = y; 2x = y; x = 5\}\) to parallel lines.
   - Convert lines \(\{x + y = 5; 2x + y = 0; x = -5\}\) to parallel lines.
   - The transformation should satisfy \( h_{33} = 1 \) and keep the point (0, 0) fixed.

### Exercise 6: Camera Calibration

6. Given a camera matrix and a 3D point in homogeneous coordinates:
   - Calculate the Cartesian coordinates of the 3D point in world space.
   - Calculate the Cartesian coordinates of the projected point in the image.
   - Compute the camera's calibration matrix for a given configuration.
   - Calculate the external transformation matrix between the camera and world coordinate systems.
   - Project a scene point (800, 150, 100) to image coordinates using the combined results of previous calculations.

## Installation

To set up the project, clone the repository and install the required dependencies:

```bash
git clone https://github.com/helenAzad/Computer-Vision_IUST.git
cd computer-vision-homework
