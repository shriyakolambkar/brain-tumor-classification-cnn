# Brain Tumor Classification using CNN

A deep learning-based approach for classifying brain MRI images into four categories using a Convolutional Neural Network (CNN).

## Overview

Brain tumor classification from MRI scans is an important task in medical image analysis. This project explores the use of deep learning to automatically classify brain MRI images into different categories.

A CNN-based model is developed to identify patterns and features in MRI images and classify them into four categories: Glioma, Meningioma, No Tumor, and Pituitary.

The project uses image preprocessing, data augmentation and a sequential CNN architecture to perform multi-class classification.

## Objectives

- Develop a CNN model for brain tumor classification using MRI images.
- Classify MRI scans into four different categories.
- Apply image preprocessing and data augmentation to support model training.
- Evaluate the model's classification performance on training and testing data.

## Dataset

The project uses the **Brain Tumor Classification (MRI)** dataset from Kaggle.

**Dataset source:** [Brain Tumor Classification (MRI) – Kaggle](https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri/data)

The dataset contains four categories:

- **Glioma Tumor**
- **Meningioma Tumor**
- **No Tumor**
- **Pituitary Tumor**

## CNN Architecture

The project implements a sequential Convolutional Neural Network consisting of:

1. **Convolutional Layers:** Three convolutional layers extract relevant visual features from MRI images, such as edges, shapes and textures.
2. **Max Pooling Layers:** Each convolutional layer is followed by a max pooling layer to downsample feature maps and reduce computational complexity.
3. **Flatten Layer:** Converts the extracted feature maps into a one-dimensional feature vector.
4. **Fully Connected Layer:** Uses the extracted features to generate output probabilities for the four classification categories.

The predicted class is selected based on the highest output probability.

## Working Principle

The overall workflow consists of the following stages:

1. **Dataset Preparation:** Load and organise MRI images into their respective class categories.
2. **Preprocessing:** Prepare the images for CNN training.
3. **Data Augmentation:** Apply augmentation to support the training process.
4. **Model Development:** Build a sequential CNN with convolutional, max pooling, flattening and fully connected layers.
5. **Model Training:** Train the network using labelled MRI images.
6. **Evaluation:** Evaluate model performance using training and testing data.
7. **Prediction:** Use the trained model to classify MRI images into one of the four categories.

## Technologies Used

- **Programming Language:** Python
- **Deep Learning:** TensorFlow, Keras
- **Image Processing:** OpenCV
- **Data Processing:** NumPy, Pandas
- **Visualisation:** Matplotlib, Seaborn
- **Development Environment:** Google Colab

## Results

The model achieved the following classification accuracy:

| Evaluation | Accuracy |
|---|---:|
| Training Accuracy | 88.70% |
| Testing Accuracy | 54.69% |

The difference between training and testing accuracy indicates that the model has scope for improvement in its generalisation performance.

## Project Resources

- **Google Colab Notebook:** [Open Brain Tumor Classification Notebook](https://colab.research.google.com/drive/1GD2gWFLGEACtlqa7qH3rB5wgiYsPF3Fb?usp=drive_link)
- **Python Source Code & Pre-trained Models:** [Access Google Drive Folder](https://drive.google.com/drive/folders/1erzqK5ay30EtwZ13_hWpqViHl1SMEaRi?usp=sharing)
- **Original Dataset:** [Kaggle – Brain Tumor Classification (MRI)](https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri/data)

The Google Drive folder contains the Python implementation and the following trained model files:

- `brain_tumor_classifier.h5`
- `brain_tumor_classifier_weights.h5`

## Applications

- Medical image analysis research.
- Automated classification of brain MRI images.
- Deep learning-based exploration of brain tumor identification.
- Educational applications in medical image processing.

## Limitations & Future Scope

The current model demonstrates the application of CNNs to multi-class brain tumor classification. However, the testing accuracy indicates that further improvements are needed.

Potential future enhancements include:

- Improving classification accuracy and generalisation.
- Exploring deeper CNN architectures and transfer learning.
- Using larger and more balanced datasets.
- Investigating brain tumor segmentation techniques.
- Evaluating the model on additional MRI datasets.

## Disclaimer

This project is an academic implementation developed for educational and research purposes. It is not intended for clinical diagnosis or as a replacement for professional medical evaluation.

---

**Project Type:** Academic / Mini Project  
**Domain:** Deep Learning | Computer Vision | Medical Image Analysis
