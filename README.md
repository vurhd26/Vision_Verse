# Vision Verse 

## Overview

This project is based on image processing techniques to enhance and analyze digital images. The process involves downsampling, quantization, edge detection, filtering, and segmentation using a variety of algorithms.

## Table of Contents

- [Downsampling and Quantization](#downsampling-and-quantization)
- [Edge Detection](#edge-detection)
  - [Canny Edge Detection](#canny-edge-detection)
  - [Hough Transform](#hough-transform)
  - [Laplacian, Sobel Gradient, Robert Edge Detector](#laplacian-sobel-gradient-robert-edge-detector)
- [Filter Techniques](#filter-techniques)
  - [Gaussian Filter](#gaussian-filter)
  - [Box Filter](#box-filter)
  - [Median Filter](#median-filter)
  - [Laplacian Filter](#laplacian-filter)
- [Segmentation](#segmentation)
  - [Normal and Otsu Thresholding](#normal-and-otsu-thresholding)
  - [K-Means Clustering](#k-means-clustering)

## Downsampling and Quantization

This phase involves reducing the resolution of the image through downsampling.
Then also adjusting the number of intensity levels using quantization techniques.

## Edge Detection

### Canny Edge Detection

Canny edge detection is employed to identify edges in the image by applying a multi-stage algorithm involving gradient calculation and non-maximum suppression.

### Hough Transform

Hough transform is utilized to detect shapes, particularly lines, in the image. This technique is valuable for identifying lines even in the presence of noise.

### Laplacian, Sobel Gradient, Robert Edge Detector

These edge detection methods are applied to highlight abrupt changes in intensity. Laplacian, Sobel Gradient, and Robert Edge Detector each offer distinct advantages in detecting edges.

## Filter Techniques

### Gaussian Filter

Gaussian filtering is implemented to blur and smooth the image, reducing noise and emphasizing important features.

### Box Filter

The box filter is used for simple smoothing, averaging pixel values in a local neighborhood.

### Median Filter

Median filtering helps in noise reduction by replacing each pixel's value with the median value in its neighborhood.

### Laplacian Filter

Laplacian filtering accentuates regions with rapid intensity changes, aiding in edge detection.

## Segmentation

### Normal and Otsu Thresholding

Normal and Otsu thresholding techniques are employed to segment the image by dividing it into distinct regions based on intensity levels.

### K-Means Clustering

K-Means clustering is utilized to group pixels into clusters based on similarity, providing insights into the image's underlying structure.

## Conclusion

This comprehensive image processing project encompasses a range of techniques to enhance, analyze, and segment digital images. Each phase contributes to a holistic approach to image manipulation and understanding.

**Happy Coding!**
