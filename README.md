# Emotion Detector

## 🧠 Overview

This project focuses on detecting emotions from facial expressions using computer vision techniques. It leverages OpenCV for face detection and a pre-trained deep learning model for emotion classification.

## 🚀 Features

- Real-time emotion detection from webcam feed.
- Supports multiple emotion categories: Happy, Sad, Angry, Surprise, Neutral, etc.
- Utilizes Haar Cascades for efficient face detection.
- Modular code structure for easy integration and scalability.

## 📁 Project Structure

```
emotion-detector/
├── EmotionDetection/
│   ├── __init__.py
│   ├── detector.py
│   └── utils.py
├── models/
│   └── emotion_model.h5
├── images/
│   └── emotion_demo.gif
├── requirements.txt
└── README.md
```

- `EmotionDetection/`: Contains the core modules for face detection and emotion classification.
- `models/`: Holds the pre-trained emotion detection model.
- `images/`: Includes demo images and GIFs.
- `requirements.txt`: Lists all Python dependencies.

## 🛠️ Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/GearHiram1397/emotion-detector.git
   cd emotion-detector
   ```

2. **Create and activate a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install the required packages:**
   ```bash
   pip install -r requirements.txt
   ```

## 🎮 Usage

1. **Run the emotion detector:**
   ```bash
   python EmotionDetection/detector.py
   ```

2. **Interact with the application:**
   - A window will open displaying the webcam feed.
   - Detected faces will be highlighted, and their corresponding emotions will be labeled.
   - Press `q` to exit the application.

## 🧪 Testing

To run unit tests (if available):

```bash
python -m unittest discover tests
```

*Ensure you have a `tests/` directory with appropriate test cases.*

## 📦 Dependencies

- Python 3.7+
- OpenCV
- TensorFlow / Keras
- NumPy
- Other dependencies listed in `requirements.txt`

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙌 Acknowledgements

- [FER-2013 Dataset](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data)
- [OpenCV](https://opencv.org/)
- [Keras](https://keras.io/)
