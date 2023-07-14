****Face Mask Recognition
**
**
This project focuses on building a face mask recognition system using deep learning and computer vision techniques. The system is designed to detect whether individuals are wearing masks or not, contributing to public health and safety.

**Table of Contents
**
Introduction

Installation

Usage

Model Training

Results

Contributing

**Introduction
**
The Face Mask Recognition project aims to provide an automated solution for mask detection. By leveraging deep learning models and computer vision algorithms, the system can accurately identify whether a person is wearing a mask or not in real-time.

The project includes the following key features:

Face detection: Utilizing a pre-trained face detection model, faces are detected within the input frame.

Mask prediction: Applying a trained deep learning model, the system predicts whether each face is wearing a mask or not.

Real-time processing: The system operates in real-time, allowing for immediate feedback on mask detection.

**Installation
**
To use the Face Mask Recognition system, follow these steps:

**Clone the repository:
**
git clone https://github.com/Graceemeruwa/face-mask-recognition.git

**Install the required dependencies:
**
pip install -r requirements.txt

**Usage
**
To run the Face Mask Recognition system, execute the following command:

bash
python main.py
The system will use your webcam to capture frames and display the live feed indicating mask-wearing status.

**Model Training
**
The face mask recognition model was trained using a deep learning architecture. The training dataset (got from Kaggle.com) consisted of images labeled as "with mask" and "without mask." 

Extensive data augmentation techniques were applied to increase the robustness of the model.

To train the model on your own dataset, follow these steps:

Organize your dataset in separate folders for "with_mask" and "without_mask" images.

Update the paths and parameters in the training script.

Run the training script.

**Results
**
The face mask recognition system has demonstrated impressive accuracy and efficiency in detecting mask-wearing status of different mask colours. 
During evaluation, the model achieved an overall accuracy of 95% on a diverse set of test images.

**Contributing**

Contributions to the Face Mask Recognition project are always welcome. If you have any suggestions, improvements, or new ideas, please submit a pull request.
