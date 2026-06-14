# Biometric Voice Assistant

## Overview

Biometric Voice Assistant is a Python-based virtual assistant that combines **facial recognition authentication** with **voice-controlled interaction**. Before accessing assistant features, users must successfully pass biometric verification through face recognition, ensuring that only authorized individuals can use the system.

The project integrates computer vision, speech recognition, and voice synthesis technologies to create a secure and interactive assistant experience.

---

## Features

### Biometric Authentication

* Face detection using OpenCV.
* Face recognition using LBPH Face Recognizer.
* User authentication before assistant activation.
* Access denied for unrecognized users.

### Voice Assistant

* Speech-to-text conversion.
* Voice command processing.
* Text-to-speech responses.
* Hands-free interaction.

### User Interface

* Interactive frontend using Eel.
* Web-based assistant interface.
* Real-time communication between frontend and backend.

---

## Technologies Used

* Python
* OpenCV
* LBPH Face Recognizer
* Speech Recognition
* pyttsx3
* Eel
* HTML
* CSS
* JavaScript

---

## System Workflow

1. User launches the application.
2. Camera captures facial data.
3. Face recognition authenticates the user.
4. If authentication is successful, the voice assistant is activated.
5. User interacts with the assistant using voice commands.
6. Assistant processes requests and provides responses.

---

## Project Structure

```text
Biometric-Voice-Assistant/
│
├── main.py
├── recoganize.py
├── trainer/
│   └── trainer.yml
├── web/
│   ├── index.html
│   ├── css/
│   └── js/
├── dataset/
└── README.md
```

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/Biometric-Voice-Assistant.git
cd Biometric-Voice-Assistant
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
python main.py
```

---

## Requirements

* Python 3.x
* Webcam
* Microphone
* OpenCV
* SpeechRecognition
* pyttsx3
* Eel

---

## Security Note

This project uses facial recognition for authentication. While it provides biometric access control, it does not currently implement advanced liveness detection or anti-spoofing mechanisms. Therefore, it is intended primarily for educational, research, and demonstration purposes.

---

## Future Enhancements

* Liveness detection.
* Multi-user support.
* Enhanced face recognition models.
* Integration with Large Language Models (LLMs).
* Improved voice command intelligence.
* Advanced security mechanisms.

---

## License

This project is intended for educational and research purposes.
