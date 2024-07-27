
# Computer Vision Basics - Assignment 8

This repository contains solutions for the eighth series of assignments for the course **Basics of Computer Vision** instructed by **Dr. Mohammadi**. The assignment covers advanced object detection techniques, including sliding window method, YOLO, SSD, Focal Loss in RetinaNet, Non-Maximum Suppression (NMS), and practical implementation of YOLO with custom datasets.

## Table of Contents

- [Introduction](#introduction)
- [Exercises](#exercises)
  - [Exercise 1: CNN with Sliding Window vs. CNN without Sliding Window](#exercise-1-cnn-with-sliding-window-vs-cnn-without-sliding-window)
  - [Exercise 2: YOLO and SSD Comparison](#exercise-2-yolo-and-ssd-comparison)
  - [Exercise 3: Non-Maximum Suppression (NMS)](#exercise-3-non-maximum-suppression-nms)
  - [Exercise 4: NMS Implementation](#exercise-4-nms-implementation)
  - [Exercise 5: YOLO Bounding Box Conversion](#exercise-5-yolo-bounding-box-conversion)
  - [Exercise 6: Training YOLO on Custom Dataset](#exercise-6-training-yolo-on-custom-dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Contributors](#contributors)
- [License](#license)

## Introduction

This assignment involves an in-depth exploration of object detection techniques, focusing on the comparison between sliding window methods and region-based approaches like YOLO and SSD. It also includes practical exercises to implement these methods and evaluate their performance.

## Exercises

### Exercise 1: CNN with Sliding Window vs. CNN without Sliding Window

1. **Answer the following questions:**
   - Discuss the computational efficiency of using a Convolutional Neural Network (CNN) with the sliding window method compared to using a CNN without this method. What are the advantages and disadvantages of this method?

   - Explain how YOLO handles multiple classes of objects within a single grid cell and predicts class probabilities along with bounding box coordinates. How do anchor boxes help in detecting objects of various shapes and sizes?

### Exercise 2: YOLO and SSD Comparison

2. **Answer the following questions:**
   - Compare YOLO and SSD (Single Shot MultiBox Detector) in terms of architecture, speed, and accuracy. Provide a detailed analysis of scenarios where one might perform better than the other.

   - Explain the concept of Focal Loss used in RetinaNet. How does this concept address the issue of class imbalance in object detection?

### Exercise 3: Non-Maximum Suppression (NMS)

3. **Explain the necessity of the Non-Maximum Suppression (NMS) technique in object detection and how it improves the performance of object detection models. Given an array of detected bounding boxes with corresponding confidence scores, explain the steps involved in applying NMS. How does changing the IoU threshold in NMS affect the results?**

### Exercise 4: NMS Implementation

4. **Apply NMS with an IoU threshold of 0.5 to the following predicted bounding boxes and list the remaining boxes:**

   ```plaintext
   {(0.9, (50, 50, 100, 100)), (0.8, (55, 60, 105, 110)), (0.7, (100, 100, 150, 150)), (0.6, (45, 50, 95, 100))}
   ```

### Exercise 5: YOLO Bounding Box Conversion

5. **Convert the following normalized YOLO bounding box coordinates to actual pixel values given an input image size of 416x416:**

   ```plaintext
   pc=0.85, bx=0.5, by=0.6, bw=0.3, bh=0.4
   ```

### Exercise 6: Training YOLO on Custom Dataset

6. **Choose an object of your choice and collect several images of it. Then, using the LabelMe tool, annotate the collected images. Train the YOLO model on the collected dataset. Finally, evaluate the model's accuracy and performance by testing it live using a webcam. Check if the model correctly detects the chosen object when placed in front of the camera.**

## Installation

Clone the repository and install the required dependencies:

```bash
git clone https://github.com/helenAzad/Computer_Vision_IUST/HW8.git
cd Computer_Vision_IUST/HW8
```

## Usage

Run the Jupyter notebooks to execute the code for each exercise:

```bash
jupyter notebook
```

Navigate to the notebook you want to run and execute the cells to see the results.

## Contributors

- **Instructor:** Dr. Mohammadi
- **Teaching Assistants:** Zamani, Azadi, Zare

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

Feel free to customize the repository URL, add any additional sections if needed, and update any specific details related to your project.