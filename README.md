# ECG Signal Classification

This repository contains code for processing and classifying Electrocardiogram (ECG) signals using various machine learning algorithms. The aim is to classify ECG signals as normal or abnormal based on their features.

## Introduction

Electrocardiogram (ECG) signals are recordings of the electrical activity of the heart. Analyzing these signals can provide valuable insights into the cardiac health of an individual. This project focuses on classifying ECG signals as either normal or abnormal using machine learning techniques.

## Dataset

The dataset used in this project is obtained from Kaggle and is derived from the PTB Diagnostic ECG Database. The dataset is available in CSV format, contains a combination of labeled normal and abnormal ECG signals. 

## Signal Processing

Before classification, the ECG signals undergo signal processing techniques to enhance their quality:

### Denoising:

The ECG signals are denoised using the bior4.4 wavelet transform, which is effective in removing noise while preserving important signal characteristics.

### Median Filtering: 

After denoising, median filtering is applied to further remove artifacts and smooth the signal. This step helps in reducing high-frequency noise and improving the signal-to-noise ratio.

## Algorithms

The following machine learning algorithms are used for classification:
1. Logistic Regression
2. Decision Tree
3. Random Forest
4. Support Vector Machine (SVM)

## Results

After training and testing the models, the script prints the accuracy and loss function values for each algorithm. Additionally, it generates heatmaps to visualize the confusion matrices.

## Contributors
1. Dana Tongsamui
2. Voravich Sriburachai 

