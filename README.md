# Driver-Drowsiness-Dataset-DDD-
The Driver Drowsiness Dataset (DDD) is an extracted and cropped faces of drivers from the videos of the Real-Life Drowsiness Dataset.
Real-Time Drowsiness Detection
Overview
This project implements a real-time drowsiness detection system using computer vision and deep learning techniques. The system leverages a trained convolutional neural network (CNN) to monitor drivers and alert them when drowsiness is detected, enhancing road safety.

Features
Real-Time Monitoring: Utilizes a webcam to continuously monitor the driver.
Drowsiness Detection: Applies a pre-trained model to classify the driver's state as "Drowsy" or "Not Drowsy".
Alarm System: Triggers an alarm sound when drowsiness is detected.
Face and Eye Detection: Uses Haar cascades for accurate face detection.
Technologies Used
Python: The programming language used for the implementation.
OpenCV: A library for computer vision tasks, used for image processing and real-time video capture.
TensorFlow/Keras: Frameworks for building and training the deep learning model.
NumPy: For numerical operations on images.
playsound: To play alarm sounds.
Code Structure
drowsiness_detection.py: Main script containing the implementation for real-time drowsiness detection.
model/: Directory containing the pre-trained model file.
alarm.mp3: Sound file used for alerts.
Contributing
Contributions are welcome! Feel free to open issues or submit pull requests to enhance the functionality or improve the project.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Thanks to the contributors of OpenCV and TensorFlow for their amazing libraries.
Special thanks to the community for providing datasets and resources for training the model.
