Import a basic libraries of python.
Load the entire model (architecture and weights) from H5 file
Load Haar cascade for face detection
Function to extract features from image
Define emotion labels
Open webcam
Convert frame to grayscale
Detect faces in the frame
Extract face region
Resize the face image to match model input shape
Extract features and normalize
Predict emotion
Draw rectangle around face
Display predicted emotion label
Display the output frame
Break the loop if 'q' is pressed
Release the webcam and close all OpenCV windows
