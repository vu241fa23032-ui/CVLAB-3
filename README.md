# Computer Vision Laboratory - Edge Detection

## Experiment: Sobel, Prewitt and Canny Edge Detection

This repository contains a Computer Vision laboratory experiment that demonstrates different image edge detection techniques using Python and OpenCV.

The experiment implements and compares three commonly used edge detection methods:

1. Sobel Edge Detection
2. Prewitt Edge Detection
3. Canny Edge Detection

The input image is first converted from a color image into a grayscale image. The three edge detection techniques are then applied to the grayscale image, and the resulting images are displayed together for comparison.

---

## Table of Contents

- [Introduction](#introduction)
- [Objectives](#objectives)
- [Problem Statement](#problem-statement)
- [Technologies Used](#technologies-used)
- [Libraries Used](#libraries-used)
- [Project Structure](#project-structure)
- [Working Principle](#working-principle)
- [Image Processing Steps](#image-processing-steps)
- [Grayscale Conversion](#grayscale-conversion)
- [Sobel Edge Detection](#sobel-edge-detection)
- [Prewitt Edge Detection](#prewitt-edge-detection)
- [Canny Edge Detection](#canny-edge-detection)
- [Implementation](#implementation)
- [How to Run](#how-to-run)
- [Input Image](#input-image)
- [Output](#output)
- [Comparison of Methods](#comparison-of-methods)
- [Advantages](#advantages)
- [Limitations](#limitations)
- [Applications](#applications)
- [Learning Outcomes](#learning-outcomes)
- [Conclusion](#conclusion)
- [Future Improvements](#future-improvements)
- [Author](#author)

---

## Introduction

Edge detection is one of the fundamental operations in Computer Vision and Digital Image Processing.

An edge represents a region in an image where there is a significant change in intensity, color, or brightness. Detecting these changes helps identify the boundaries of objects and important structures within an image.

Edge detection is widely used as a preprocessing step in many Computer Vision applications. It can simplify an image by reducing the amount of information while preserving the important structural information.

In this experiment, three edge detection techniques are implemented using OpenCV:

- Sobel
- Prewitt
- Canny

The output from each technique is compared to understand their behavior and effectiveness.

---

## Objectives

The main objectives of this experiment are:

- To understand the concept of edge detection.
- To understand image gradients.
- To convert a color image into grayscale.
- To implement Sobel edge detection.
- To implement Prewitt edge detection.
- To implement Canny edge detection.
- To apply convolution kernels to an image.
- To compare different edge detection techniques.
- To visualize the results using Matplotlib.
- To understand the importance of edge detection in Computer Vision.

---

## Problem Statement

Given an input image, detect the important edges and boundaries present in the image using different edge detection algorithms.

The input image is processed using:

```text
Input Image
     |
     v
Grayscale Conversion
     |
     +-------------------+
     |         |         |
     v         v         v
   Sobel    Prewitt    Canny
     |         |         |
     +---------+---------+
               |
               v
        Result Comparison
## Conclusion

The experiment successfully demonstrated the implementation of three important edge detection techniques: Sobel, Prewitt, and Canny using Python, OpenCV, NumPy, and Matplotlib.

The input image was first converted into a grayscale image and then processed using the three different edge detection methods. The Sobel operator detected edges by calculating intensity gradients in the horizontal and vertical directions. The Prewitt operator used convolution kernels to identify directional changes in the image. The Canny algorithm was used to detect clear and well-defined edges using suitable threshold values.

The results of all three techniques were displayed together, allowing a direct comparison of their edge detection performance. The experiment demonstrated that different edge detection algorithms produce different representations of the boundaries present in the same image.

Overall, this experiment provided practical knowledge of image preprocessing, grayscale conversion, convolution, image gradients, edge detection, and image visualization. These concepts form an important foundation for advanced Computer Vision applications.

The experiment achieved its objective of understanding and comparing Sobel, Prewitt, and Canny edge detection techniques and provided a practical understanding of how edge information can be extracted from digital images.
