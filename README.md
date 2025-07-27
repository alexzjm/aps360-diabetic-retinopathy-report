# Diabetic Retinopathy Detection using Deep Learning

This project explores the use of convolutional neural networks and transfer learning to classify stages of diabetic retinopathy (DR) from retinal fundus images. Developed as part of the University of Toronto’s **APS360: Applied Fundamentals of Deep Learning** course.

## Overview

- Implemented and compared several CNN architectures (VGG16, AlexNet, EfficientNet, SqueezeNet)
- Used transfer learning to extract features, followed by a custom MLP classifier
- Addressed class imbalance with data augmentation and undersampling
- Evaluated on both internal and external test sets for real-world generalizability

## Results

- Best model: VGG16 + 3-layer MLP with ~53.2% testing accuracy
- Baseline: Random Forest with ~38.3% accuracy
- Visualized feature maps to interpret CNN behavior
- Found challenges with recall and generalization, especially for early-stage DR

## Key Concepts

- Transfer learning with feature extraction
- Data preprocessing (blurring, contrast normalization)
- Class balancing and augmentation
- Evaluation using precision, recall, F1, and confusion matrix

## Ethical Considerations

The model is not intended for clinical use and should only assist optometrists. Dataset diversity and explainability remain key concerns.
