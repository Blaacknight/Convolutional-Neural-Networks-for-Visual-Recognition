# Lecture 2 | Image Classification

## Overview
This lecture discusses the fundamentals of image classification, challenges, and common approaches such as k-nearest neighbors and convolutional neural networks (CNNs).

## Key Points

- **Definition of Image Classification (05:35)**
  - The system receives an input image and assigns it a label from a predetermined set (e.g., cat, dog, truck).
  - Humans find this easy, but it's a complex task for machines.

- **How Computers See Images (05:57 - 07:28)**
  - Images are represented as a grid of numbers (pixel values).
  - Challenges include object deformation, occlusion, and variations in appearance.

- **Writing an Image Classifier (09:23 - 11:20)**
  - A naïve approach would involve writing a function that maps images to labels, but this is not scalable.
  - A better approach is a data-driven method that generalizes well to various objects.

- **K-Nearest Neighbors (KNN) Approach (15:19 - 19:07)**
  - Finds the nearest training example and assigns its label.
  - Efficient for small datasets but slow at test time.
  - Uses vectorized NumPy operations for implementation.

- **Distance Metrics (24:45 - 27:04)**
  - L1 distance follows coordinate axes, while L2 (Euclidean) distance is rotation-invariant.
  - Choice of metric depends on the problem domain.

- **Training, Validation, and Test Sets (31:18 - 33:32)**
  - Training set: Used for learning.
  - Validation set: Used for hyperparameter tuning.
  - Test set: Evaluates final model performance.
  - Ensures robustness of the classifier.

- **Problems with KNN (39:17 - 41:25)**
  - Slow test-time performance.
  - Requires exponential training examples for high-dimensional spaces.
  - Not practical for large-scale image classification.

- **Introduction to Deep Learning (13:16 - 35:19)**
  - Data-driven approaches like CNNs are more scalable.
  - Deep learning has revolutionized image classification in the last two decades.

## Conclusion
- KNN is a simple but impractical approach for image classification.
- CNNs and deep learning provide a more scalable and efficient solution.
- Proper dataset partitioning is essential for reliable model evaluation.
