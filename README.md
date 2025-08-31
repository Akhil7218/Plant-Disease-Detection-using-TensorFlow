# Plant Disease Detection using TensorFlow

This project develops an advanced deep learning pipeline for automated plant disease detection using TensorFlow and ResNet-based transfer learning. Leveraging the New Plant Diseases Dataset (Augmented), the model learns to accurately classify various plant diseases from leaf images, enabling early detection and supporting better agricultural practices.

The project benefits farmers, agricultural researchers, and precision farming systems by reducing dependency on manual disease identification and accelerating disease management in crops.

**Key Advantages:**  
- Uses state-of-the-art TensorFlow/Keras APIs for preprocessing and augmentation  
- Leverages ResNet transfer learning for powerful feature extraction and fine-tuning  
- Works with a large, augmented dataset to avoid overfitting  
- Provides a foundation for real-world deployment in smart farming solutions

---
 
## Table of Contents

- [Introduction](#introduction)
- [Dataset & Preprocessing](#dataset--preprocessing)
- [Model Architecture](#model-architecture)
- [Training & Evaluation](#training--evaluation)
- [Installation & Usage](#installation--usage)
- [Documentation](#documentation)
- [Contributions](#contributions)

---

## Introduction

This repository contains a robust deep learning model for plant disease detection, built with TensorFlow and optimized via ResNet backbone transfer learning. Advanced preprocessing and augmentation techniques are used to improve generalization and accuracy.

## Dataset & Preprocessing

- Dataset: New Plant Diseases Dataset (Augmented)
- Structure: Training, validation, and testing folders
- Preprocessing:  
  - Normalize pixel values  
  - Resize images to 224×224 pixels  
  - Apply augmentation for robust generalization

## Model Architecture

- ResNet backbone for feature extraction
- Custom fully connected dense layers for classification
- Classifies multiple disease categories with high accuracy

## Training & Evaluation

- Batch-wise learning on GPUs
- Adam/SGD optimizers
- Accuracy and loss metrics monitoring
- Strong generalization and validation performance across datasets

## Installation & Usage

**Installation:**  
1. Clone this repository:  
2. Install required dependencies:  
3. Download and prepare the New Plant Diseases Dataset (Augmented)
4. Run the notebook `plant-disease-detection.ipynb`

**Usage:**  
- Train the model by executing notebook cells sequentially  
- Evaluate model accuracy using validation and test datasets  
- Predict disease class for new plant leaf images

## Documentation

- The notebook includes extensive documentation, dataset distribution analysis, example images, and performance plots.
- Additional documentation will be added with future project developments and deployment modules.

## Contributions

Contributions are welcome! Potential enhancements:
- Add new deep learning backbones (EfficientNet, DenseNet, etc.)
- Improve data augmentation pipelines
- Integrate model deployment (TensorFlow Lite, web/mobile apps)
- Optimize training for larger datasets

---

Feel free to open issues or submit pull requests to improve this project!
