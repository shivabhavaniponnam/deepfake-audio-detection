DeepFake Audio Detection
AI-Based System to Detect Real vs Fake Audio

DeepFake Audio Detection is a machine learning-based web application that analyzes audio files and predicts whether the audio is real or AI-generated (fake). It uses a trained ML model integrated with a Python backend and a simple frontend interface.

🚀 Live Demo

Experience the project live here
👉 https://demo-deepfake-audio-detection.netlify.app/
✨ Features
Upload audio file for analysis
Detects real vs fake audio using ML model
Fast prediction using trained scaler + model
Simple and responsive web UI
Backend API integration using FastAPI/Flask
Stores and processes audio data securely
Real-time prediction system
🔔 Call Alert system when suspicious/fake audio is detected
Instant notification/alert on detection result
🛠 Tech Stack

Frontend:
HTML, CSS, JavaScript

Backend:
Python (FastAPI / Flask), Uvicorn

Machine Learning:
Scikit-learn, NumPy, Librosa

Database:
SQLite (if used in project)

🗂 Project Structure
📦 deepfake-audio-detection
│
├── 📂 backend
│   ├── 📂 database
│   ├── 📂 models
│   ├── 📂 routes
│   ├── 📂 services
│   ├── 📂 uploads
│   ├── 📄 main.py
│   ├── 📄 db.py
│   ├── 📄 tables.py
│   ├── 📄 deepguard.db
│
├── 📂 frontend
│   ├── 📄 index.html
│   ├── 📄 about.html
│   ├── 📄 analytics.html
│   ├── 📄 detect.html
│   ├── 📄 history.html
│   ├── 📄 call-detection.html
│   ├── 📂 assets
│
├── 📂 model
│   ├── 📄 deepfake_model.pkl
│   ├── 📄 scaler.pkl
│
├── 📂 dataset
│
├── 📄 README.md
⚙️ How It Works
User uploads an audio file
Frontend sends file to backend API
Backend extracts audio features using Librosa
ML model processes features
System predicts:
✅ Real Audio
❌ Fake Audio
🔔 If fake audio is detected → Call Alert is triggered
📞 Call Alert Feature
If suspicious or fake audio is detected
System triggers alert notification
Can be extended to:
Phone call alert (Twilio API)
Email alert
UI popup warning
