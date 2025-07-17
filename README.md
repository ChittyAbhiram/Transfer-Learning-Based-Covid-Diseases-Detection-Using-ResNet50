# Transfer-Learning-Based-Covid-Diseases-Detection-Using-ResNet50

This project implements a deep learning pipeline using ResNet50 to classify CT scan images as either COVID-19 or non-COVID. The dataset is preprocessed by resizing and normalizing images, and labels are one-hot encoded. It includes exploratory data analysis (EDA), data augmentation, model training with callbacks for learning rate adjustment and checkpointing, and evaluation via accuracy/loss plots and confusion matrix. The model architecture integrates ResNet50 as a feature extractor with custom dense layers for classification. Additionally, the script allows single image inference for real-time predictions. This project demonstrates an end-to-end workflow for medical image classification using transfer learning.


