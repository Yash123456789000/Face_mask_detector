# Face_mask_detector

A deep learning project that detects face mask compliance in real-time video streams. Built using **VGG-16** and **MobileNet V2** models with **OpenCV** and **Keras**, this application provides a visual notification for individuals wearing or not wearing a mask, making it ideal for integration in public safety systems, surveillance, and smart office solutions.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technical Details](#technical-details)
- [Results](#results)

---

## Overview

This project implements a real-time face mask detection system to identify if individuals are wearing a mask. The system uses transfer learning with **VGG-16** and **MobileNet V2** architectures, leveraging **Haar Cascade** for accurate face detection. The application detects faces in a video stream and classifies each face as "Mask" or "No Mask," displaying the result on the video feed.

---

## Features

- Real-time video processing and face mask detection
- Transfer learning with **VGG-16** and **MobileNet V2** for high accuracy
- Lightweight design for deployment on embedded systems like **Raspberry Pi**
- Visual notification on the video feed indicating mask compliance
- Easily customizable for additional classes or different detection settings

---

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/face-mask-detector.git
   cd face-mask-detector
clone and use it in your google collab or any IDE


## Technical Details

- **Model Architecture**: Transfer learning is applied with VGG-16 for feature extraction and MobileNet V2 for lightweight, efficient classification.
- **Face Detection**: Haar Cascade Classifier is used to detect faces within frames.
- **Real-Time Processing**: OpenCV handles video stream processing to continuously detect faces and classify mask compliance.
- **Libraries**: This project uses Python, Keras, TensorFlow, OpenCV, and NumPy.

## Results
The model achieved a high accuracy rate of 96% on the validation set. Real-time performance is optimized for lower latency on embedded devices like Raspberry Pi, making it suitable for real-world applications.
