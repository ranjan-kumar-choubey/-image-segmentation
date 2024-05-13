# image-segmentation
Mean-Shift Clustering for Image Segmentation

## Overview
This project implements the Mean-Shift Clustering algorithm in Python to perform image segmentation. The algorithm segments an image by clustering pixel values in the feature space and assigns each pixel to a cluster, which helps in distinguishing different regions in the image.

## Implementation Details

### 1. Mean-Shift Clustering Implementation
- **Algorithm**: The mean-shift clustering algorithm is implemented in Python. It takes parameters such as bandwidth (radius of the search window) and the number of iterations to converge.
- **Inputs**: Bandwidth (radius), number of iterations.
- **Outputs**: Cluster centers and corresponding labels for each data point.

### 2. Image Loading
- **Library Used**: Python image processing libraries such as OpenCV or PIL are used to load images for processing.

### 3. Image Preprocessing
- **Color Space Conversion**: The image is converted from RGB to LAB color space to better suit clustering.
- **Flattening**: The image is flattened into a 2D array to serve as input for the clustering algorithm.

### 4. Application of Mean-Shift for Image Segmentation
- **Segmentation**: The mean-shift algorithm is applied to the preprocessed image data to segment the image into different regions.
- **Visualization**: The segmented image is visualized by coloring each pixel according to the color of its cluster center.

### 5. Experimentation and Evaluation
- **Parameter Tuning**: Different values for the bandwidth are experimented with to observe their effects on the quality of segmentation.
- **Qualitative Evaluation**: The segmentation results are evaluated qualitatively by visually inspecting the segmented images.


