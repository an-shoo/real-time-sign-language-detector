# real-time-sign-language-detector
This project is a real-time sign language gesture detection system using Python, OpenCV for image capture, and TensorFlow's Object Detection API. It leverages Transfer Learning with a pre-trained SSD MobileNet model to detect and classify five specific sign language gestures.

Features
Real-Time Detection: Detects and classifies sign language gestures using webcam input.

Gesture Set: Detects five sign language gestures: "Hello", "Yes", "No", "Thank You", and "I Love You".

Transfer Learning: Utilizes transfer learning with the SSD MobileNet model for efficient and accurate detection.

Technologies Used
Python: Programming language for implementation.

OpenCV: For capturing real-time images from the webcam.

TensorFlow Object Detection API: For model training and inference.

SSD MobileNet: A pre-trained model used with transfer learning to detect objects (sign language gestures).

LabelImg: Tool used for labeling the dataset with bounding boxes.

Setup Instructions
Prerequisites:
Python 3.x installed on your system.

Basic knowledge of Python and TensorFlow.

Webcam for real-time detection.

Dataset:
The dataset consists of images of five sign language gestures, captured using the webcam.

Labeling the dataset is done manually using the LabelImg tool.

Model Training:
Prepare the dataset: Capture and label the images using LabelImg.

Train the model: Use transfer learning with the pre-trained SSD MobileNet model from TensorFlow.

Follow the steps in the TensorFlow Object Detection API tutorial for fine-tuning the model on your labeled dataset.

Real-Time Detection:
To run the real-time detection script:

bash
Copy
Edit
python detect_sign_language.py
This will start a webcam feed where the trained model will detect and classify the gestures in real time.
