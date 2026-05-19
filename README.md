# 🎧 DeepFake Audio Detection System  
### AI-Based System to Detect Real vs Fake Audio

DeepFake Audio Detection is a machine learning-based web application that analyzes uploaded audio files and predicts whether the audio is **real or AI-generated (fake)**. It uses a trained ML model with a Python backend and a simple frontend interface.

---

## 🚀 Live Demo
👉 https://demo-deepfake-audio-detection.netlify.app/

---

## ✨ Features

- Upload audio file for analysis  
- Detects real vs fake audio using ML model  
- Fast prediction using trained scaler + model pipeline  
- Simple and responsive web UI  
- Backend API integration (FastAPI / Flask)  
- Secure audio processing  
- Real-time prediction system  
- Alert system when fake audio is detected  

---

## 🛠 Tech Stack

**Frontend:**
- HTML
- CSS
- JavaScript

**Backend:**
- Python
- FastAPI / Flask
- Uvicorn

**Machine Learning:**
- Scikit-learn
- NumPy
- Librosa

**Database (Optional):**
- SQLite

---

## 📁 Project Structure

```
deepfake-audio-detection/
│
├── backend/
│   ├── database/
│   ├── models/
│   ├── routes/
│   ├── services/
│   ├── uploads/
│   ├── main.py
│   ├── db.py
│   ├── tables.py
│
├── frontend/
│   ├── index.html
│   ├── about.html
│   ├── analytics.html
│   ├── detect.html
│   ├── history.html
│   ├── call-detection.html
│   └── assets/
│
├── model/
│   ├── deepfake_model.pkl
│   ├── scaler.pkl
│
├── dataset/
│
└── README.md
```

---

## ⚙️ How It Works

1. User uploads an audio file  
2. Frontend sends file to backend API  
3. Backend extracts features using Librosa  
4. ML model predicts whether audio is real or fake  
5. If fake → alert is triggered  

---

## 📞 Alert System

- Detects suspicious/fake audio  
- Shows instant warning in UI  
- Can be upgraded to:
  - Twilio phone call alerts  
  - Email notifications  

## 📌 Future Improvements

- Real-time voice streaming detection  
- Twilio call alert integration  
- Mobile app version  
- Deep learning models (CNN/RNN/Transformer)  
- Cloud database support  

