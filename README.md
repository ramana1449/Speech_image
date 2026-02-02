Speech to Image Generation using MonsterAPI

A Python-based AI project that converts spoken audio in any language into a generated image using speech recognition, translation, and generative AI.

🚀 Project Overview

This project allows users to:

Speak in any language (Telugu, Hindi, Tamil, English, etc.)

Convert speech to text using OpenAI Whisper

Translate detected text to English

Generate an AI image from the speech using MonsterAPI

🧠 Architecture Flow
Audio Input (Any Language)
        ↓
Speech to Text (Whisper)
        ↓
Translation to English
        ↓
Text Prompt
        ↓
Image Generation (MonsterAPI)
        ↓
Output Image

📁 Project Folder Structure
speech_to_image/
│
├── requirements.txt
├── .env
│
├── data/
│   ├── audio/
│   │   └── input.wav
│   ├── text/
│   │   ├── detected_text.txt
│   │   └── translated_prompt.txt
│   └── images/
│       └── output.png
│
└── src/
    ├── record_audio.py
    ├── speech_to_text.py
    ├── translate_text.py
    ├── generate_image.py
    └── main.py
