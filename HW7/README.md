
# Computer Vision Basic - Assignment 7

This repository contains solutions for the seventh series of assignments for the course **Basics of Computer Vision** instructed by **Dr. Mohammadi**. The assignment covers advanced topics in convolutional neural networks, including dilated convolutions, depthwise separable convolutions, template matching, semantic segmentation, and object detection with Fast R-CNN.

## Table of Contents

- [Introduction](#introduction)
- [Exercises](#exercises)
  - [Exercise 1: Dilated Convolutions](#exercise-1-dilated-convolutions)
  - [Exercise 2: Depthwise Separable Convolutions](#exercise-2-depthwise-separable-convolutions)
  - [Exercise 3: Template Matching](#exercise-3-template-matching)
  - [Exercise 4: Segment Anything Model (SAM)](#exercise-4-segment-anything-model-sam)
  - [Exercise 5: Semantic Segmentation with U-Net](#exercise-5-semantic-segmentation-with-u-net)
  - [Exercise 6: Object Detection with Fast R-CNN](#exercise-6-object-detection-with-fast-r-cnn)
- [Installation](#installation)
- [Usage](#usage)
- [Contributors](#contributors)
- [License](#license)

## Introduction

This assignment involves a deep dive into various advanced CNN techniques, including dilated convolutions, depthwise separable convolutions, template matching, semantic segmentation using U-Net, and object detection using Fast R-CNN. The exercises require both theoretical understanding and practical implementation of these techniques.

## Exercises

### Exercise 1: Dilated Convolutions

1. **Study the following link and answer the questions:**
   - [Variants of Pooling and Convolution](https://medium.com/jun94/variants-pooling-and-convolution-13-devpblog/dl-94a282ff5c-aspp-spp-convolution-dilated) (20 points)

   a) For a convolutional layer with kernel size \( k \) and dilation rate \( d \), write the dimensions of the dilated kernel in terms of \( k \) and \( d \).
   
   b) If the dilation rate of a convolutional layer is tripled, how many times does the number of trainable parameters increase?
   
   c) Fill in the missing values in the table:

   | Layer        | 1   | 2   | 3   | 4  | 5  | 6   | 7    | 8       |
   |--------------|-----|-----|-----|----|----|-----|------|---------|
   | Convolution  | 3x3 | 3x3 | 3x3 | 3x3| 3x3| 5x5 | 5x5  | E x E   |
   | Dilation rate| 1   | 1   | 4   | B  | 8  | 3   | 2    | 6       |
   | Receptive field | 3x3 | 5x5 | A   | 35x35 | C  | D   | 71x71 | 107x107 |

   d) Consider a network with two convolutional layers with kernel size 5 and three max pooling layers. To achieve a minimum receptive field of 107x107, what is the minimum required stride for the max pooling layers?

### Exercise 2: Depthwise Separable Convolutions

2. **Study the following link and compare the parameters and operations of a standard convolutional layer with a depthwise separable convolutional layer:** 
   - [Introduction to Depthwise Separable Convolutions](https://towardsdatascience.com/a-basic-introduction-to-separable-convolutions-b99ec3102728) (10 points)

   a) Given an input of (128,128,3), kernel size 5, and 64 filters, calculate the parameters and operations for both convolution types.

   b) If the input dimensions of a standard convolutional layer are (32, 12, 12), kernel size is 3x3, and the number of output filters is 32, how many times more parameters are required if using depthwise convolution?

### Exercise 3: Template Matching

3. **Consider the following input image and template, and determine the appropriate match duration:**
   - Input Image
   - Template (20 points)

   a) Provide reasoning for the match duration.

   b) Using template matching, find all coins in the given image:

   ```
   53 181 200 151 255 253 255
   200 7 29 3 200 199 218
   91 21 18 5 220 255 255
   96 2 14 11 219 254 253
   112 217 211 199 218 251 253
   6 27 3
   21 18 5
   2 15 11
   ```

### Exercise 4: Segment Anything Model (SAM)

4. **Complete the SAM notebook to segment images and generate high-quality masks for objects:**
   - Fill in the specified sections and execute the code to reach the final output. (10 points)

### Exercise 5: Semantic Segmentation with U-Net

5. **Refer to the `semantic_segmentation` notebook and complete the required sections:** 
   - Add appropriate callbacks to save the best model.
   - Train a U-Net from scratch.
   - Train a U-Net with a pre-trained encoder. In the first phase, freeze the encoder and train only the decoder. In the second phase, fine-tune the entire network.
   - Provide explanations for your code and brief explanations for the pre-written sections. (25 points)

### Exercise 6: Object Detection with Fast R-CNN

6. **Complete the `Q6` notebook to perform object detection with Fast R-CNN:**
   - Use TensorFlow for this task.
   - Download and load the Pascal VOC dataset.
   - Convert annotations to the required format, such as labels and bounding boxes.
   - Write a function to display 10 images with their annotations (labels and bounding boxes).
   - Load a pre-trained Fast R-CNN model using the following code:
     ```python
     model = tf.keras.applications.ResNet50(include_top=False, input_shape=(None, None, 3))
     ```
   - Write a function to perform inference on each image using the Fast R-CNN model.
   - Evaluate the model using the validation set and compute the following metrics:
     1. Mean Average Precision (mAP)
     2. Precision
     3. Recall
     4. F1 Score
     5. Confusion Matrix
   - Plot the Precision-Recall curve. (35 points)

## Installation

Clone the repository and install the required dependencies:

```bash
git clone https://github.com/helenAzad/Computer_vision_IUST/HW7.git
cd Computer_Vision_IUST/HW7
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
- **Teaching Assistants:** Nadari Fard, Ghayouri, Mirakhorloo

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

Feel free to customize the repository URL, add any additional sections if needed, and update any specific details related to your project.