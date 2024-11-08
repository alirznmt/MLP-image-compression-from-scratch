# Neural Network Implementation for Image Compression: Multi-Layer Perceptron (MLP) and Adaptive Approaches

This repository implements a neural network-based approach for **image compression** using **multi-layer perceptron (MLP)** models. The project includes both basic and adaptive neural network architectures designed to compress and decompress images. The adaptive method optimizes compression by utilizing different networks based on the complexity of image blocks.

## Project Overview

This project demonstrates the application of neural networks, particularly MLPs, for lossy image compression. The basic neural network architecture compresses images by reducing redundancies, while the adaptive approach improves compression quality by dynamically selecting networks according to image block complexity.

- **Objective**: To develop neural network models capable of compressing grayscale images effectively, with minimal loss in quality.
- **Image Complexity**: Image blocks are divided based on complexity, measured using Entropy, Activity, and Pattern-based methods. Each complexity level is compressed by a specific network to maintain the quality of compressed images.

## Key Features

- **Multi-Layer Perceptron (MLP) Model**: A simple neural network structure for basic image compression.
- **Adaptive Neural Networks**: Different networks are used for compressing image blocks depending on their complexity levels, which are calculated based on Entropy, Activity, or Pattern-based measurements.
- **Complexity Measurement Techniques**:
  - **Entropy**: Measures the information content of each block.
  - **Activity**: Measures intensity changes across pixels.
  - **Pattern-based Complexity**: Divides blocks based on pre-defined patterns for more accurate compression.
- **Performance Metrics**:
  - **Peak Signal-to-Noise Ratio (PSNR)**: Used to evaluate the quality of the decompressed images.
  - **Compression Ratio (CR)**: Reflects the efficiency of the compression.

## Repository Structure

- **Data**: Contains sample images for training and testing.
- **Scripts**: Code for training MLP and adaptive networks, testing routines, and performance evaluation.
- **Results**: Documentation of performance metrics (PSNR and CR) for various configurations.

## Citing the Work

This implementation is based on the paper:

> Veisi, H., & Jamzad, M. (2009). A Complexity-Based Approach in Image Compression using Neural Networks. *International Journal of Signal Processing, 5*(2), 82-92. Available at [WASET](https://www.waset.org).

