# Emotion-Recognition-Using-CNN

## Project Overview

This project aims to build a Convolutional Neural Network (CNN) model for recognizing emotions from facial expressions. The model is trained on images of human faces and classifies them into seven emotional categories: angry, disgusted, fearful, happy, neutral, sad, and surprised.

This repository contains all the necessary files, including the trained model, code, and images used for the training process.

---

## Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)
3. [Dataset](#dataset)
4. [Model Architecture](#model-architecture)
5. [Results](#results)
6. [License](#license)

---

## Installation

To run this project on your local machine, follow these instructions.

### Prerequisites

Make sure you have Python 3.x installed and have `pip` to install packages.

### Steps to Install

1. Clone the repository:
   ```bash
   git clone https://github.com/tnerler/Emotion-Recognition-Using-CNN.git
   cd Emotion-Recognition-Using-CNN
   ```

2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

---

## Usage

To run the emotion recognition model, use the following steps:

1. Download the dataset and place it in the project folder (make sure the data is in the correct directory format).
2. Run the `emotion_detection.py` script:
   ```bash
   python emotion_detection.py
   ```
3. The script will read an image file, detect faces, and predict the emotion of the face. You can use your own images for testing.

---

## Dataset

The dataset used for training the CNN model is the **[FER-2013](https://www.kaggle.com/datasets/priya07/fer2013)** dataset, which contains labeled images of various human emotions.

---

## Model Architecture

The model is based on a Convolutional Neural Network (CNN) that consists of the following layers:

1. **Convolutional layers** with ReLU activation functions.
2. **MaxPooling layers** for dimensionality reduction.
3. **Batch Normalization** for improving the model’s performance.
4. **Fully connected layers** with Dropout for regularization.
5. **Softmax output layer** to classify the input image into one of the seven emotion categories.

---
## Evaluate

![Loss Result](https://github.com/tnerler/Emotion-Recognition-Using-CNN/blob/main/screenshots/loss.png)

![Accuracy Result](https://github.com/tnerler/Emotion-Recognition-Using-CNN/blob/main/screenshots/accuracy.png)
---
## Results

![Sample Result](https://github.com/tnerler/Emotion-Recognition-Using-CNN/blob/main/screenshots/happy.jpeg)

![Happy Emotion](https://github.com/tnerler/Emotion-Recognition-Using-CNN/blob/main/screenshots/happy_output.jpeg)

---
![Sample Result](https://github.com/tnerler/Emotion-Recognition-Using-CNN/blob/main/screenshots/disgusted.jpg)

![Disgusted Emotion](https://github.com/tnerler/Emotion-Recognition-Using-CNN/blob/main/screenshots/disgusted_output.jpg)


---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

