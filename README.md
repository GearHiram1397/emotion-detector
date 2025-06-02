# Emotion Detector

## 🧠 Overview

This is a simple text-based emotion detection project using IBM Watson NLP. The app sends user-provided text to a Watson API endpoint and returns the predicted emotion scores (anger, joy, sadness, etc.) and the dominant emotion.

## 🚀 Features

- Text input–based emotion analysis
- Utilizes IBM Watson’s NLP API for emotion prediction
- Flask-based web interface for input and results
- Simple and modular code

## 🗂 Project Structure

```
emotion-detector/
├── EmotionDetection/
│   ├── __init__.py
│   ├── emotion_detection.py
│   └── test_emotion_detection.py
├── static/
│   └── mywebscript.js
├── templates/
│   └── index.html
├── .gitignore
├── LICENSE
└── README.md
```

## 🛠️ Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/GearHiram1397/emotion-detector.git
   cd emotion-detector
   ```

2. **Create and activate a virtual environment (optional):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required packages:**
   ```bash
   pip install -r requirements.txt
   ```

## ▶️ Usage

You can use the main emotion detector function from `emotion_detection.py`:

```python
from EmotionDetection.emotion_detection import emotion_detector

result = emotion_detector("I am feeling very happy today!")
print(result)
# Output: {'anger': 0.0, 'disgust': 0.0, 'fear': 0.01, 'joy': 0.98, 'sadness': 0.01, 'dominant_emotion': 'joy'}
```

## 🧪 Testing

Run the test file to validate your implementation:

```bash
python EmotionDetection/test_emotion_detection.py
```

## 📦 Dependencies

- Python 3.7+
- `requests`
- `json`
- Flask (if using web interface)

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
