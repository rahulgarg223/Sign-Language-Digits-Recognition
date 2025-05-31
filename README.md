# Sign Language Digits Recognition

A computer vision and deep learning project for recognizing American Sign Language (ASL) digits (0–9) from hand gesture images using Convolutional Neural Networks (CNNs). This project is particularly useful for developing communication aids for deaf people.

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

## 🔍 Overview

This project aims to classify hand signs of digits (0 to 9) in American Sign Language (ASL) using deep learning. The model takes an image as input and predicts the corresponding digit, making it a valuable tool for developing sign language interpretation systems.

## 📊 Dataset

- **Source:** Kaggle - Sign Language Digits Dataset
- **Classes:** 10 digits (0–9)
- **Samples:** 2,000+ grayscale images per digit
- **Image Size:** 28x28 pixels

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/rahulgarg223/Sign-Language-Digits-Recognition.git
   cd Sign-Language-Digits-Recognition
   ```

2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

## 🏗️ Model Architecture

The project uses a Convolutional Neural Network (CNN) architecture with the following key components:
- Input layer for 28x28 grayscale images
- Multiple convolutional layers with ReLU activation
- MaxPooling layers for dimensionality reduction
- Dense layers for classification
- Softmax output layer for 10 digit classes

## 🎯 Training & Evaluation

1. Prepare your dataset in the following structure:
   ```
   data/
   ├── train/
   │   ├── 0/
   │   ├── 1/
   │   └── ...
   └── test/
       ├── 0/
       ├── 1/
       └── ...
   ```

2. Run the training script:
   ```bash
   python sign_language_digits_recognition.py
   ```

## 📈 Results

- High accuracy in digit recognition
- Real-time processing capability
- Robust performance across different hand positions and lighting conditions

## 🛠️ Technologies Used

- Python
- TensorFlow/Keras
- OpenCV
- NumPy
- Matplotlib
- Jupyter Notebook

## 💻 Usage

The project can be used in two ways:

1. Using the Jupyter Notebook:
   - Open `Sign_Language_Digits_Recognition.ipynb`
   - Run cells sequentially to train and test the model

2. Using the Python script:
   - Run `sign_language_digits_recognition.py`
   - Follow the command-line prompts for training and testing

## 🔮 Future Work

- Extend to full sign language alphabet recognition
- Implement real-time video processing
- Add support for multiple sign languages
- Improve model accuracy and robustness
- Develop a user-friendly interface

## 👥 Contributors

- [Rahul Garg](https://github.com/rahulgarg223)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Dataset provided by [Kaggle Sign Language Digits Dataset](https://www.kaggle.com/datasets/ardamavi/sign-language-digits-dataset)
- Inspired by various computer vision and deep learning research papers
