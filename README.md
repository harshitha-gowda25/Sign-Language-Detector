#Sign Language Detector
A real-time sign language detection system using Python, OpenCV, and deep learning to recognize hand gestures and translate them into text.

Features:

Detects and classifies sign language gestures in real-time.
Uses a trained deep learning model for accurate recognition.
Implements OpenCV for image processing and hand tracking.
Displays the recognized gesture as text on the screen.

Installation:

1. Clone the repository
2. Create a virtual environment
3. Install Requirements
4. Run collect_imgs.pu
5. Run create_dataset.py -> This will generate data.pickle file
6. Run train_classifier.py -> This will generate model.p file
7. Run inference_classifier.py

Usage:

1. Ensure your webcam is connected.
2 Run the script, and the system will start detecting sign language gestures.
3. The recognized gestures will be displayed as text in real-time.

Technologies Used: 
Python, OpenCV, TensorFlow/Keras (for deep learning model), MediaPipe (for hand tracking)
   
