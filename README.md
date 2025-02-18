
# 🎭 Gesture & Emotion Recognition AI  

## 🚀 Overview  
This project is a **gesture and facial-expression-based AI system** that detects hand gestures and facial expressions using **MediaPipe** and a **deep learning model**. The model is trained to recognize gestures and emotions and apply them in **real-world applications**, such as:  
- **Real-time emotion-based music recommendations** 🎶  
- **Gesture-based interaction** 🖐️  

## ✨ Features  
✅ **Real-time gesture and facial recognition** using **MediaPipe**  
✅ **Trainable deep learning model** with **TensorFlow/Keras**  
✅ **Interactive AI applications** (e.g., emotion-based song recommendations)  
✅ **Webcam-based real-time predictions**  
✅ **Easy-to-use Streamlit UI**  

---

## 🛠️ Technologies Used  
- 🎥 **MediaPipe** - Real-time landmark detection  
- 🤖 **TensorFlow/Keras** - Model training and inference  
- 🎮 **OpenCV** - Video processing  
- 🎶 **Streamlit + WebRTC** - Web-based interface for emotion detection  
- 📝 **NumPy** - Data handling and storage  

---

## 📂 Project Structure  

| File | Description |
|------|------------|
| `data_collection.py` | Collects gesture and facial expression data using **MediaPipe** |
| `data_training.py` | Trains a **deep learning model** on collected data |
| `inference.py` | Runs real-time predictions using the trained model |
| `music.py` | Detects emotions and recommends songs based on mood |

---

## 📥 Installation  

### 🔹 Prerequisites  
Ensure you have **Python 3.8+** installed. Install dependencies using:  

```bash
pip install -r requirements.txt


🔹 Running the Project
1️⃣ Collect Training Data

```bash
python data_collection.py

Press Esc to stop when enough data is collected.

2️⃣ Train the Model

```bash
python data_training.py

This saves a trained model as model.h5.

3️⃣ Run Real-time Predictions

```bash
python inference.py

The model will predict gestures/emotions in real-time.

4️⃣ Run the Music Recommendation App

```bash
streamlit run music.py

Detects your emotion and suggests YouTube songs accordingly.

 Usage
🎭 Gesture Recognition

Displays real-time gesture and emotion predictions on screen.

🎵 Emotion-Based Music Recommendation

Detects your mood and recommends songs on YouTube.

🖐️ Interactive Gesture-Controlled Applications

Can be extended to control applications using gestures.

 Future Enhancements
🚀 More Emotion & Gesture Categories
📈 Improved Deep Learning Model for Better Accuracy
🎨 Gesture-Based UI Control for Hands-Free Navigation

 Contributing
Contributions are welcome! Feel free to submit issues or pull requests.


