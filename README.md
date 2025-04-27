# ASL Gesture Recognition using Deep Learning

This repository contains three different approaches to recognize American Sign Language (ASL) gestures using deep learning techniques. The models used in this project include:

- Custom Convolutional Neural Network (CNN)
- MediaPipe Hand Tracking with a Pre-trained CNN model
- Transfer Learning using Pre-trained models (e.g., MobileNetV2)

---

## Table of Contents

- [Overview](#overview)
- [Setup](#setup)
- [Models](#models)
  - [Custom CNN](#custom-cnn)
  - [MediaPipe](#mediapipe)
  - [Transfer Learning](#transfer-learning)
- [Requirements](#requirements)
- [How to Run](#how-to-run)
- [License](#license)


---

## Overview

The goal of this project is to classify ASL gestures into corresponding letters. We approach this task using three different models, each with its unique methodology and technique. 

1. **Custom CNN**: A custom-built CNN is trained on ASL gesture images to recognize gestures and map them to the corresponding alphabet.
2. **MediaPipe**: MediaPipe is used for hand tracking and feature extraction. The extracted features are fed into a pre-trained CNN for gesture classification.
3. **Transfer Learning**: A pre-trained model (like MobileNetV2) is fine-tuned on the ASL dataset to recognize gestures, leveraging the power of transfer learning.

---

## Models

### Custom CNN
This model is a custom Convolutional Neural Network (CNN) that is built and trained specifically to recognize ASL gestures.  
The model uses multiple convolutional layers followed by fully connected layers for classification.

### MediaPipe
This approach uses **MediaPipe** to track hands in real-time and extract features, which are then passed through a pre-trained CNN model for gesture classification.  
MediaPipe allows for efficient hand tracking and feature extraction, simplifying the recognition process.

### Transfer Learning
Transfer Learning is applied by fine-tuning a pre-trained CNN model, such as **MobileNetV2**, on the ASL dataset.  
This method leverages the knowledge of a pre-trained model and applies it to solve the ASL gesture recognition task.

---

## Setup

### Clone this repository:

```bash
git clone https://github.com/yourusername/yourrepository.git
cd yourrepository
```

---

### Requirements

- tensorflow
- mediapipe
- opencv-python
- numpy
- matplotlib

```bash
pip install -r requirements.txt
```

---

### Install dependencies:

```bash
pip install -r requirements.txt
```

---

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

### ✨ Key Points
- **Overview**: Brief description of the project.
- **Setup**: Clear instructions for installing dependencies and running notebooks.
- **Models**: Short explanations for each approach.
- **License**: Open-source under MIT License.
