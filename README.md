# Final Project

## Emotion Detection using Watson NLP

This project is the final assignment for the IBM Skills Network course.

The application uses the IBM Watson NLP Emotion Prediction service to analyze a given text and detect the following emotions:

- Anger
- Disgust
- Fear
- Joy
- Sadness

The application also identifies the dominant emotion and displays the result through a Flask web interface.

## Project Structure

```
oaqjp-final-project-emb-ai/
│
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
│
├── static/
│
├── templates/
│   └── index.html
│
├── server.py
├── test_emotion_detection.py
├── requirements.txt
└── README.md
```

## Features

- Detects emotions using IBM Watson NLP
- Returns scores for five emotions
- Identifies the dominant emotion
- Handles invalid or blank input
- Includes unit tests
- Flask web interface
- Static code analysis using Pylint (10/10)

## Technologies Used

- Python 3
- Flask
- Requests
- IBM Watson NLP
- Pylint
- Unittest

## How to Run

### Install dependencies

```bash
pip install -r requirements.txt
```

### Start the application

```bash
python3 server.py
```

Open your browser and visit:

```
http://localhost:5000
```

## Run Unit Tests

```bash
python3 test_emotion_detection.py
```

## Run Static Code Analysis

```bash
pylint server.py
```

Expected output:

```
Your code has been rated at 10.00/10
```

## Author

Arun Chauhan