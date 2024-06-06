# Emotion Detection using CNN, VGG16, and ResNet50 🧠🎨

## Overview
- Utilizes the [FER2013 dataset](https://www.kaggle.com/datasets/msambare/fer2013) dataset from Kaggle for emotion detection in facial images.
- Imports data into Google Colab using Kaggle API and sets up directories.
- Performs data cleaning, analysis, and visualization.
- Plots one image from each class and random images for shape and channel inspection.
- Explores four models: Scratch CNN, Data Augmentation CNN, VGG16, and ResNet50.

### Model Performance
| Model                    | Final Train Accuracy | Final Validation Accuracy | Training Epochs |
|--------------------------|----------------------|---------------------------|-----------------|
| Scratch CNN              | 62.82                | 55.42                     | 10              |
| Data Augmentation CNN    | 37.90                | 41.39                     | 10              |
| VGG16                    | 58.08                | 57.01                     | 5               |
| ResNet50 (Early Stopped) | 63.50                | 63.01                     | 35              |
