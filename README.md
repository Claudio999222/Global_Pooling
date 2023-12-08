# Global Pooling in Convolutional Neural Networks (CNN)

## Overview

This notebook explores the utilization of Global Pooling, specifically Global Average Pooling and Global Max Pooling, in Convolutional Neural Networks (CNNs). Global Pooling is a technique used for dimensionality reduction in CNN architectures, replacing fully connected layers in some cases. It helps reduce the number of parameters and computational cost, potentially preventing overfitting.

## Key Objectives:

1. **Introduction to Global Pooling**: Understand the concept of Global Pooling and its role in CNNs.

2. **Global Average Pooling (GAP)**: Implement Global Average Pooling and observe its effects on model architecture and training.

3. **Global Max Pooling (GMP)**: Implement Global Max Pooling and compare its performance with Global Average Pooling.

4. **Dimensionality Reduction**: Explore how Global Pooling reduces the spatial dimensions of the feature maps.

5. **Comparison with Fully Connected Layers**: Understand the advantages and limitations of using Global Pooling instead of fully connected layers.

## Considerations:

- Global Average Pooling computes the average value of each feature map, while Global Max Pooling selects the maximum value.
- Global Pooling reduces the spatial dimensions to a single value per feature map.
- It helps in preventing overfitting and reduces the risk of too many parameters.

This notebook provides a hands-on demonstration of implementing Global Pooling in CNNs and comparing the effects of Global Average Pooling and Global Max Pooling on model architecture and training.
