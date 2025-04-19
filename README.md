# Sign Language Digits Recognition  
![License](https://img.shields.io/badge/license-MIT-blue.svg)

A computer vision and deep learning project for recognizing American Sign Language (ASL) digits (0–9) from hand gesture images using Convolutional Neural Networks (CNNs).

---

## 📌 Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Model Architecture](#model-architecture)
- [Training & Evaluation](#training--evaluation)
- [Results](#results)
- [Technologies Used](#technologies-used)
- [Usage](#usage)
- [Future Work](#future-work)
- [Contributors](#contributors)
- [License](#license)

---

## 🔍 Overview

This project aims to classify hand signs of digits (0 to 9) in **American Sign Language (ASL)** using deep learning. The model takes an image as input and predicts the corresponding digit. This can be helpful for developing sign language interpretation tools for communication aids.

---

## 📊 Dataset

- **Source:** [Kaggle - Sign Language Digits Dataset](https://www.kaggle.com/datasets/datamunge/sign-language-mnist)
- **Classes:** 10 digits (0–9)
- **Samples:** 2,000+ grayscale images per digit
- **Image Size:** 28x28 pixels

---

## ⚙️ Installation

Clone the repository:
```bash
git clone https://github.com/your-username/sign-language-digit-recognition.git
cd sign-language-digit-recognition


pip install -r requirements.txt

Input (28x28x1) →
Conv2D(32 filters, 3x3) + ReLU →
MaxPooling(2x2) →
Conv2D(64 filters, 3x3) + ReLU →
MaxPooling(2x2) →
Flatten →
Dense(128) + ReLU →
Dropout(0.5) →
Dense(10) + Softmax


