# Image Segmentation using Lazy Snapping and K-Means Clustering from Scratch
## Overview
This Jupyter Notebook demonstrates image segmentation techniques using two popular methods: Lazy Snapping and K-means clustering. The objective is to partition the images into meaningful segments based on pixel intensity similarities and user-defined masks. This notebook showcases how different values of K impact the segmentation quality and compares the results of both algorithms. 

## Dependencies
- Jupyter Notebook 
- Python
- NumPy
- matplotlib
- 
## Features
- Image Segmentation: Segment images using Lazy Snapping and K-Means Clustering.
- Comparison of Segmentation Quality: Evaluate the impact of k values (2, 4, 8, 16) on segmentation.
- Visual Representation: Display the original and segmented images in a grid for easy comparison.
![image](https://github.com/areeba0/Image-Segmentation-with-Lazy-Snapping-and-K-Means-Clustering/assets/136759791/fac30c6e-2435-4203-b11f-1f4efa7261d8)

# Implementation
The notebook is structured into several key steps:
## 1)K-Means Clustering:
- Implement the K-Means algorithm to partition the image into k clusters based on pixel intensity similarities.
- Update centroids iteratively until convergence.
  
## 2)Lazy Snapping:
- Extract seed pixels from user-defined foreground and background masks.
- Compute the likelihood of each pixel belonging to the foreground or background class.
- Assign pixels to classes based on likelihood values to obtain segmented images.
  
## 3)Visualization:
Display the original image and its segmented counterparts obtained through Lazy Snapping and K-Means Clustering for different 
k values.
![image](https://github.com/areeba0/Image-Segmentation-with-Lazy-Snapping-and-K-Means-Clustering/assets/136759791/a976828c-89f1-4365-bc73-bcf9c7ef2d66)

# Usage
- Load the Image: Load the image along with the foreground and background masks.
- Set Values of k: Specify different values of k to observe the impact on segmentation.
#### -Segmentation Process:
  - Use the Lazy Snapping method to segment the image based on user-defined masks and seed pixels.
  - Apply K-Means Clustering to partition the image into k clusters.
  - Visualize Results: Display the original and segmented images in a grid for comparison.


