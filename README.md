📌 Semester 6

# Ocular Disease Identification using Deep Learning

A deep learning model to detect ocular diseases from retinal images using transfer learning.

## Problem

Early detection of eye diseases like diabetic retinopathy is difficult and requires expert analysis.

## Solution

This project uses deep learning to:
- Analyze retinal fundus images
- Automatically detect ocular diseases
- Assist in faster and accurate diagnosis

## Features

- CNN-based image classification
- Transfer learning using ResNet50
- Data augmentation for better performance
- Grad-CAM visualization for interpretability

## Tech Stack

- Python
- TensorFlow
- Keras
- ResNet50

## How it Works

1. Input retinal image is preprocessed
2. Data augmentation improves dataset quality
3. ResNet50 extracts deep features
4. Model classifies disease type
5. Grad-CAM highlights important regions

## Results

- 92% classification accuracy
- Improved performance using transfer learning
- Visual explanation of predictions using heatmaps

## How to Run

```bash
git clone https://github.com/your-username/-Deep-Learning-Insights-into-Ocular-Disease-Identification.git
cd -Deep-Learning-Insights-into-Ocular-Disease-Identification
pip install -r requirements.txt
python main.py
