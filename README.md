# Emotion-Based Music Recommender

This project is a **real-time emotion detection and music recommendation system** that uses facial and hand landmarks to detect emotions and recommend music based on the detected emotion. The system is built using Python and leverages several libraries, including Mediapipe, OpenCV, Keras, and Streamlit.


## Overview

The project consists of four main components:
1. **Data Collection**: Collects facial and hand landmark data from the user's webcam.
2. **Model Training**: Trains a neural network model using the collected data.
3. **Real-Time Inference**: Performs real-time emotion detection using the trained model.
4. **Music Recommendation**: Integrates the emotion detection model with a Streamlit web app to recommend music based on the detected emotion.

## Features

- **Real-Time Emotion Detection**: Detects emotions in real-time using facial and hand landmarks.
- **Music Recommendation**: Recommends music based on the detected emotion, user's preferred language, and singer.
- **Interactive Web Interface**: Provides a user-friendly web interface using Streamlit.
- **Customizable**: Users can input their preferred language and singer for personalized recommendations.

## Technologies Used

- **Mediapipe**: For detecting facial and hand landmarks.
- **OpenCV**: For capturing and processing video frames.
- **Keras/TensorFlow**: For building, training, and deploying the neural network model.
- **Streamlit**: For creating the web interface.
- **WebRTC**: For real-time video streaming in the Streamlit app.
- **NumPy**: For handling numerical data and array operations.
- **Webbrowser**: For opening YouTube search results.

## Setup and Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/emotion-based-music-recommender.git
   cd emotion-based-music-recommender

2. **Install Dependencies**:
    Ensure you have Python 3.7 or higher installed. Then, install the required dependencies using the following command:

   ```bash
   pip install -r requirements.txt

  
