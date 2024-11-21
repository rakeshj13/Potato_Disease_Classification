# Plant Disease Classification Using TensorFlow

This project implements a deep learning model to classify potato plant leaves into three categories: `Potato___Early_blight`, `Potato___Late_blight`, and `Potato___healthy`. It uses TensorFlow's Keras API to build, train, and evaluate a convolutional neural network (CNN) for this task.

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Model Architecture](#model-architecture)
4. [Results](#results)

---

## Project Overview

The goal of this project is to automate the classification of plant leaf images to identify diseases or healthy leaves. This can assist farmers in identifying issues early and taking appropriate measures.

Key features:
- Data preprocessing, including augmentation and partitioning.
- CNN architecture with multiple layers of convolution and max-pooling.
- Model evaluation and visualization of results.
- Model saving and prediction on new samples.

---

## Dataset

The dataset used is from the **PlantVillage** dataset. The project focuses on three classes:
- `Potato___Early_blight`
- `Potato___Late_blight`
- `Potato___healthy`
- 
---

## Model Architecture

The model is a convolutional neural network (CNN) with the following layers:
- Input resizing and rescaling.
- Data augmentation (random flipping and rotation).
- Six convolutional layers with ReLU activation and max pooling.
- Flattening layer.
- Dense layers for classification.

---

# Results

## Model Accuracy

- **Training Accuracy:** 97.51%  
- **Validation Accuracy:** 97.92%  
- **Test Accuracy:** 98.54%  

## Example Predictions

Below are some example predictions made by the model:

| Image                 | Predicted Label        | Confidence |
|-----------------------|------------------------|------------|
| `Potato___healthy`    | Potato___healthy       | 99.2%      |
| `Potato___Early_blight` | Potato___Early_blight | 98.5%      |
| `Potato___Late_blight`  | Potato___Late_blight  | 97.8%      |

