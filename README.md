# Melanoma Image Classification Project

This project focuses on the classification of images into two categories: those containing melanoma, a type of skin cancer, and those that do not. The classification is achieved using Convolutional Neural Networks (CNNs) trained on image data obtained from [Kaggle](https://www.kaggle.com/datasets/bhaveshmittal/melanoma-cancer-dataset).

## Overview

Melanoma is a serious form of skin cancer, and early detection is crucial for successful treatment. This project aims to develop a model capable of accurately identifying melanoma in images, which could assist dermatologists and medical professionals in diagnosis.

## Project Structure

The project consists of the following components:

1. **Data Preprocessing**: The `data_preprocessing.ipynb` notebook contains code for preprocessing the image data, including loading, shuffling, normalization, and splitting into training, validation, and testing sets.

2. **CNN Model**: The `CNN_model.ipynb` notebook implements the CNN architecture for image classification. It defines the neural network architecture, trains the model on the preprocessed data, and evaluates its performance.

## Usage

To use this project:

1. **Download Dataset**: Download the melanoma image dataset from [Kaggle](https://www.kaggle.com/datasets/bhaveshmittal/melanoma-cancer-dataset).

2. **Data Preparation**: Organize the dataset into appropriate directories (`../data/train` and `../data/test`).

3. **Data Preprocessing**: Execute the `data_preprocessing.ipynb` notebook to preprocess the data, including loading, shuffling, and splitting.

4. **Model Training**: Run the `CNN_model.ipynb` notebook to define, train, and evaluate the CNN model for image classification.

5. **Evaluation and Analysis**: Analyze the model's performance using metrics such as loss curves, accuracy, classification reports, and confusion matrices.

## Dependencies

Ensure you have the following dependencies installed to run the notebooks:

- Python (>=3.6)
- PyTorch
- torchvision
- NumPy
- Matplotlib
- Seaborn
- scikit-learn
