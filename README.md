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

3. **Run the Data Collection Script**:

   Use the data_collection.py script to collect facial and hand landmark data.

   Run the script:
   ```bash
   python data_collection.py

 Follow the prompts to enter the name of the data (e.g., "happy", "sad").

 The script will capture 100 samples of facial and hand landmarks and save them in a .npy file.

4. **Train the Model**:

   After collecting data for multiple emotions, use the data_training.py script to train the model.

   Run the script:
   ```bash
   python data_training.py

The script will load all .npy files in the directory, train a neural network model, and save it as model.h5.

It will also save the labels in labels.npy.

5. **Run the Inference Script**:

   Use the inference.py script to perform real-time emotion detection.

   Run the script:
   ```bash
   python inference.py
   
The script will use your webcam to detect facial and hand landmarks, predict the emotion, and display it on the screen.

Press the Esc key to stop the script.

6. **Run the Streamlit App**:

   Use the music.py script to launch the Streamlit web app for music recommendation.

   Run the script:
   ```bash
   streamlit run music.py

The app will open in your browser. Input your preferred language and singer, and let the app detect your emotion.

Click the "Recommend me songs" button to get music recommendations based on your emotion.


## Usage
**Data Collection**
Run data_collection.py to collect facial and hand landmark data for different emotions.

The collected data will be saved as .npy files (e.g., happy.npy, sad.npy).

**Model Training**
Run data_training.py to train the neural network model using the collected data.

The trained model will be saved as model.h5, and the labels will be saved as labels.npy.

**Real-Time Emotion Detection**
Run inference.py to perform real-time emotion detection using your webcam.

The detected emotion will be displayed on the video feed.

**Music Recommendation**
Run music.py to start the Streamlit web app.

Input your preferred language and singer.

The app will detect your emotion and recommend music based on your inputs.

Click the "Recommend me songs" button to open YouTube search results with the recommended songs.

## Project Structure

**emotion-based-music-recommender/**
├── data_collection.py       # Script for collecting facial and hand landmark data
├── data_training.py         # Script for training the neural network model
├── inference.py             # Script for real-time emotion detection
├── music.py                 # Streamlit app for music recommendation
├── model.h5                 # Trained model (generated after training)
├── labels.npy               # Labels for the trained model (generated after training)
├── emotion.npy              # Temporary file to store the detected emotion
├── requirements.txt         # List of dependencies
└── README.md                # Project documentation
