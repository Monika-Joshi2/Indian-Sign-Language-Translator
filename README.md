# Indian Sign Language (ISL) to Text Conversion System

This project aims to bridge the communication gap between the hearing and speech impaired by translating Indian Sign Language (ISL) gestures into text in real-time.

## **Features**
- **Gesture Recognition**: Detects and recognizes hand gestures using a camera.
- **Text Translation**: Converts recognized gestures into text within 2 seconds.
- **User Preferences**: Includes options to add letters, clear text, or reset sentences.
- **High Accuracy**: Achieved 93% real-time accuracy despite varying lighting conditions, perfect accuracy with feed images.

## **Technology Stack**
- **Random Forest Classifier**: For gesture recognition and classification.
- **OpenCV**: For hand detection and gesture tracking.
- **Python**: Core programming language.

## **How It Works**
1. Opens the camera to scan and verify hand positions.
2. Allows users to perform gestures, which are then recognized and translated into text.
3. Displays translated text with user-friendly controls for editing.

