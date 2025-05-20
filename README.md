# Sign_language_detection-using-teachable-machine
This project leverages Teachable Machine's image model framework to create a user-friendly application that identifies various hand gestures via webcam input. It includes pre-trained TensorFlow.js models and demonstrates real-time prediction capabilities using a browser-based interface.

Features

-Real-Time Prediction: Utilizes a webcam to predict gestures in real-time.

-Pre-Trained Model: Built with a custom model trained using Teachable Machine.

-Multi-Gesture Support: Recognizes 10 different gestures: Namaskar, OK, Love, Super, Hi, Not OK, Shakehand, Swag, Two, Circle.

-Easy Integration: Uses TensorFlow.js for lightweight deployment.

Requirements:

-A modern web browser that supports JavaScript.

-Webcam access for real-time gesture predictions.

How to Run

1.Clone this repository to your local machine:

git clone https://github.com/yourusername/teachable-machine-image-model.git

2.Navigate to the project directory:

cd teachable-machine-image-model

3.Serve the project using a local HTTP server (e.g., Python’s built-in server):

python3 -m http.server

4.Open your browser and visit http://localhost:8000.

Dependencies

TensorFlow.js: For running the model in a web environment.

Teachable Machine Image: For model training and deployment.
