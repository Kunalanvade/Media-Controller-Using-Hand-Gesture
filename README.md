# Media Controller Using Hand Gesture
Media Controller Using Hand Gesture is an innovative Python application that enables hands-free control of media playback through gesture recognition. The project harnesses the power of OpenCV and MediaPipe to detect hand gestures in real-time using a webcam.

# Key Features:
Gesture Recognition: Utilizes MediaPipe's hand tracking to identify hand landmarks and count fingers.
Control Commands: Maps specific hand gestures to media control commands:
One Finger: Simulates the "right" arrow key to move forward.
Two Fingers: Simulates the "left" arrow key to move backward.
Three Fingers: Simulates the "up" arrow key.
Four Fingers: Simulates the "down" arrow key.
Five Fingers: Simulates the "space" key to play/pause media.

# How It Works:
Capture Video: The application captures video from the webcam using OpenCV.
Hand Detection: MediaPipe processes the video to detect hand landmarks.
Gesture Analysis: The system counts the number of fingers extended and determines the corresponding media control command.
Execute Commands: Uses PyAutoGUI to simulate keypresses based on detected gestures.
This system provides a convenient, touch-free way to control media playback, enhancing user interaction with multimedia content.
