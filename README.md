# 🌿 Plant Disease Detection — Deep Learning

> 📚 INFO-6152: Deep Learning with TensorFlow & Keras 2 | Fanshawe College

## Overview
Automated plant disease detection using three deep learning architectures 
applied to the PlantVillage dataset (54,000+ leaf images, 38 classes).

## 🏆 Results

| Model | Val Accuracy | Val Loss | Training Time |
|-------|-------------|----------|---------------|
| Custom CNN | **94.3%** | 0.231 | 59.1 min |
| CNN + LSTM | 26.9% | 2.915 | 22.1 min |
| Transfer Learning (MobileNetV2) | 94.2% | **0.173** | 57.8 min |

## 🔬 Models
- **Custom CNN** — 3 Conv blocks (32→64→128 filters)
- **CNN + LSTM** — CNN features reshaped into sequence for LSTM
- **Transfer Learning** — MobileNetV2 pretrained on ImageNet, 2-phase fine-tuning

## 🛠️ Tech Stack
Python • TensorFlow/Keras • NumPy • Matplotlib • Google Colab (T4 GPU)

## 📊 Dataset
PlantVillage — 54,000+ images, 38 plant disease classes
