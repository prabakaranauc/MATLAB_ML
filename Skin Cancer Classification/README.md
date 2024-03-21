# Skin Cancer Classification

This repository contains code for skin cancer classification using MATLAB. It includes feature extraction, data preprocessing, and classification using Neural Network and Naive Bayes algorithms.

## Table of Contents
- [Introduction](#introduction)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Dependencies](#dependencies)
- [License](#license)

## Introduction
Skin cancer is a significant public health concern, and early detection is crucial for effective treatment. This project aims to classify skin lesions as malignant or benign using machine learning techniques. 

### Feature Extraction
Feature extraction is a critical step in machine learning-based classification tasks. In this project, we extract features from images of skin lesions to characterize their texture and color information. These features help in distinguishing between malignant and benign lesions.

### Data Preprocessing
Before feeding the data into machine learning algorithms, preprocessing steps are performed to ensure data quality and compatibility. This includes resizing images, segmenting lesions, and extracting relevant features using techniques like Gray Level Co-occurrence Matrix (GLCM).

### Classification Algorithms
Two classification algorithms are implemented in this project:

1. **Neural Network**: Neural networks are powerful machine learning models inspired by the human brain. In this project, a feedforward neural network is trained on the extracted features to classify skin lesions.

2. **Naive Bayes**: Naive Bayes is a probabilistic classifier based on Bayes' theorem with strong independence assumptions. It is commonly used for classification tasks, including medical diagnosis. Here, it's applied to classify skin lesions based on the extracted features.

## Usage
To use this code:

1. **Feature Extraction**: Run `malignant_feature_extraction.m` and `benign_feature_extraction.m` scripts to extract features from images of malignant and benign skin lesions, respectively.

2. **Combine Data**: Run `combine_data.m` to combine the extracted features into a single CSV file for classification.

3. **Classification**: Execute `classification.m` to load the combined data, preprocess it, split it into training and validation sets, and perform classification using Neural Network and Naive Bayes algorithms. It computes performance metrics such as sensitivity, specificity, accuracy, and confusion matrices.

## File Structure
- `malignant_feature_extraction.m`: Script for extracting features from malignant skin lesions.
- `benign_feature_extraction.m`: Script for extracting features from benign skin lesions.
- `combine_data.m`: Script for combining extracted features into a single CSV file.
- `classification.m`: Script for classification using Neural Network and Naive Bayes algorithms.
- `GLCM_features1.m`: Function to compute GLCM features.
- `boundingBox.m`: Function to calculate the bounding box of segmented regions.
- `data23.xlsx`: Excel file containing additional data.
- `MASK.JPG`: Mask image for segmentation.

## Dependencies
- MATLAB R2018a or later
- Image Processing Toolbox

## License
This project is licensed under the GNU General Public License v3.0 - see the [GNU General Public License v3.0](LICENSE) file for details.

