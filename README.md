# Diabetic Retinopathy Grading using Deep Learning

This project focuses on the automatic detection and grading of diabetic retinopathy using deep learning techniques applied to retinal fundus images.

## Overview

Diabetic retinopathy is a leading cause of blindness. Early detection through automated systems can significantly improve diagnosis and treatment.

This project explores multiple convolutional neural network (CNN) architectures for classification and grading tasks.

## Models Used

- InceptionV3 (Binary Classification)
- MobileNetV2 (Grading)
- Image preprocessing using morphological transformations

## Project Structure

- `notebooks/` – Jupyter notebooks with experiments and model implementations  
- `report/` – Final academic report  
- `presentation/` – Project presentation slides  

## Techniques

- Data preprocessing and augmentation  
- Transfer learning  
- CNN-based classification  
- Performance evaluation  

## Tools & Technologies

- Python  
- TensorFlow / Keras  
- OpenCV  
- Jupyter Notebook  

## Results

The models demonstrate the effectiveness of deep learning in detecting diabetic retinopathy from retinal images, with promising classification performance.

## Author

Chaima Ahmed Gaid  
Amira Temmam

## Model Performance Comparison

The following table summarizes the performance of different deep learning models for diabetic retinopathy classification.

| Model           | Accuracy | Precision | Recall | F1-Score |
|----------------|----------|----------|--------|----------|
| EfficientNetB1 | 83.46%   | 0.84     | 0.83   | 0.82     |
| InceptionV3    | 87.43%   | 0.87     | 0.87   | 0.87     |
| MobileNetV2    | **87.88%** | **0.88** | **0.88** | **0.87** |
| Xception       | 86.31%   | 0.86     | 0.86   | 0.86     |

### Analysis

MobileNetV2 achieved the highest overall accuracy (87.88%) with balanced precision and recall, making it the most effective model for this task. InceptionV3 also demonstrated strong and stable performance across both classes. EfficientNetB1 showed lower recall for the diabetic retinopathy (DR) class, indicating limitations in detecting positive cases.

These results highlight the effectiveness of lightweight CNN architectures for medical image classification tasks.
