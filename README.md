Farm Assistant Hub 🌾
Farm Assistant Hub is a smart agriculture support system designed for farmers and agriculture enthusiasts. It leverages AI and weather data to provide crop consultation, disease detection, crop disease risk assessment, and a community forum — all through a friendly web interface.

This repository includes both the backend (Flask API) and frontend (UI files).

🔥 Features
🎯 AI Farm Consultant ("Plantie"): Smart, conversational farming advice using Google Gemini AI.

📸 Crop Disease Detection: Upload images to detect crop diseases with AI.

🌦 Indian Crop Disease Risk Assessment: Predict disease risks based on real-time weather data.

📝 Community Forum: Users can register, post farming queries, comment, and like posts.

🌎 Multilingual Translator: Communicate in your preferred language.

🔐 Authentication System: Secure user registration and login.

📦 MongoDB Integration: For user, posts, comments, and disease info storage.

📤 Image Upload Support: For posts and disease detection.

🧠 Cloud-Based AI Models: Uses Google Gemini, OpenAI Whisper, and TensorFlow Lite.

🏗️ Project Structure
├── app.py                # Main Flask backend server
├── static/                # Static assets (uploaded images, etc.)
├── templates/             # Frontend HTML templates (UI files)
├── requirements.txt       # Python dependencies
└── README.md              # (This file)
🧠 Tech Stack
Backend: Python, Flask, Flask-CORS

Frontend: HTML, CSS (Static Templates)

Database: MongoDB (NoSQL)

AI Services:

Google Gemini AI (Chat & Image Analysis)

OpenAI Whisper (Audio Transcription)

TensorFlow Lite (Local ML)

Cloud APIs:

OpenWeatherMap (Weather Data)

Google Translate (Language Support)

