# Intelligent AI Doctor with Vision and Voice

**Author:** Tanmay Mishra  
**GitHub:** [https://github.com/Tanmay0001/Intelligent-AI-Doctor-with-Vision-and-Voice](https://github.com/Tanmay0001/Intelligent-AI-Doctor-with-Vision-and-Voice)  
**Hugging Face Space:** [https://huggingface.co/spaces/Tanmaymishra09/Intelligent-AI-Doctor](https://huggingface.co/spaces/Tanmaymishra09/Intelligent-AI-Doctor)

---

## Overview

**Intelligent AI Doctor** is an AI based application that integrates **llm** and **voice processing** to assist doctors in diagnosing diseases. The application allows users to provide patient information through **voice** or **text input** and uses AI models to analyze symptoms and provide insights or recommendations.

This project demonstrates the integration of:

- **Text-to-Speech and Speech-to-Text processing**  
- **Image analysis for skin or other medical conditions**  
- **AI driven recommendation and diagnosis suggestions**  
- **Interactive web interface with Gradio**

---

## Features

- **Voice Interaction:** Users can describe symptoms via voice and the AI can respond naturally using text-to-speech.  
- **Image Analysis:** Upload images of affected areas for automated analysis.  
- **Text Input Option:** Alternative to voice, users can type symptoms for diagnosis.  
- **Gradio Web Interface:** User friendly interface for real time interaction.  
- **Cross platform Deployment:** Deployed on Hugging Face Spaces for cloud access.

---

# Getting Started

## Set Up Virtual Environment
```python -m venv venv
.\venv\Scripts\activate    # Windows
source venv/bin/activate   # macOS/Linux```

## Install Dependencies
```pip install -r requirements.txt```

## Running the Application Locally
```python app.py```


Open the URL displayed in your terminal (usually http://127.0.0.1:7860) to access the interface.

You can test voice input, text input and image upload features.

Deployment on Hugging Face Spaces

Ensure your main script is named app.py.

Push the project to your Hugging Face Space repository.

Hugging Face automatically detects app.py and builds the space.

If the build doesn’t start automatically, go to: Settings → Advanced → Restart Space.



## Technologies Used

Python 3.x

Gradio for web interface

PyTorch / TensorFlow (for AI/ML models)

SpeechRecognition / pyttsx3 / ElevenLabs API for voice processing

OpenCV / PIL for image handling
