# Lecture 2 | Image Classification

## Overview
This lecture discusses the fundamentals of image classification, challenges, and common approaches such as k-nearest neighbors and convolutional neural networks (CNNs).

## Key Points

- **Definition of Image Classification**
  - Image classification involves assigning an input image to one of several predefined categories.
  - The system processes an image (e.g., a cat) and determines its label from a fixed set (e.g., cat, dog, truck, plane).
  - While humans find visual recognition intuitive, it is a complex task for machines.

- **How Computers See Images**
  - Unlike humans, computers do not perceive images as holistic objects but as a grid of numerical values representing pixel intensities.
  - Objects in images can vary significantly in appearance due to factors like lighting, angle, deformation, and occlusion.
  - Robust algorithms are required to handle these variations effectively.

- **Writing an Image Classifier**
  - A naïve approach involves manually coding a function to classify images, but this is not scalable.
  - Instead, machine learning models use data-driven techniques to generalize across various objects and scenarios.
  - The goal is to develop algorithms that can classify images accurately without being explicitly programmed for every possible scenario.

- **K-Nearest Neighbors (KNN) Approach**
  - KNN classifies an image by finding the most similar training example and assigning its label.
  - It is conceptually simple but inefficient for large datasets due to slow test-time performance.
  - Uses vectorized NumPy operations for efficient computation.
  - KNN can be improved by considering multiple nearest neighbors (k-nearest) and taking a majority vote.

- **Distance Metrics in Classification**
  - L1 (Manhattan) distance measures similarity based on coordinate differences and follows grid-like paths.
  - L2 (Euclidean) distance is rotation-invariant and measures straight-line distance.
  - The choice of metric impacts classifier performance and should be selected based on the problem domain.

- **Training, Validation, and Test Sets**
  - The dataset is typically split into:
    - **Training set**: Used to train the model.
    - **Validation set**: Used to tune hyperparameters and prevent overfitting.
    - **Test set**: Used to evaluate final model performance on unseen data.
  - Proper partitioning ensures the classifier generalizes well to new inputs.

- **Problems with KNN**
  - Computationally expensive at test time, making it impractical for large-scale tasks.
  - Requires an exponential number of training examples to cover high-dimensional data adequately.
  - Sensitive to noise and irrelevant features, leading to potential misclassification.

- **Introduction to Deep Learning**
  - Data-driven approaches like convolutional neural networks (CNNs) are more scalable and efficient for image classification.
  - Deep learning has significantly improved image recognition performance over the past two decades.
  - CNNs extract hierarchical features from images, making them robust to variations and distortions.

## Conclusion
- KNN is a simple but inefficient approach for image classification due to slow test-time performance and scalability issues.
- CNNs and deep learning provide a more practical and powerful solution for large-scale image classification.
- Proper dataset partitioning and selection of distance metrics are crucial for building effective classifiers.
- This lecture sets the foundation for understanding how deep learning has revolutionized image recognition.
