# 🧠 NeuroDetect

AI-Powered Parkinson's Disease Detection System using Computer Vision and Voice Biomarker Analysis.

---

## 📖 Overview

NeuroDetect is a full-stack Artificial Intelligence application designed for the early detection of Parkinson's Disease using motor skill analysis and voice biomarker analysis.

The system performs a multi-modal assessment by analyzing:

- Spiral Graphometry Drawings
- Voice Recordings
- Machine Learning Predictions
- Clinical-style Diagnostic Reports

The platform aims to assist healthcare professionals and researchers by providing rapid, automated screening of Parkinsonian symptoms.

---

## ✨ Features

### 🎯 Motor Skill Analysis
- Spiral drawing upload
- Image preprocessing
- Feature extraction
- Parkinson's pattern detection

### 🎤 Voice Biomarker Analysis
- Audio upload and processing
- Frequency analysis
- Jitter and shimmer extraction
- Voice-based Parkinson's prediction

### 🤖 AI-Based Prediction
- Machine Learning models
- Confidence scoring
- Combined diagnostic assessment

### 🔐 Secure Authentication
- Google OAuth Login
- Protected Dashboard
- Secure User Sessions

### 📄 Diagnostic Reporting
- Clinical-style report generation
- Confidence metrics
- Individual modality results
- Combined assessment

---

## 🏗️ System Architecture

```text
User
 │
 ▼
React Frontend
 │
 ├── Google Authentication
 │
 ├── Spiral Image Upload
 │
 └── Voice Recording Upload
 │
 ▼
FastAPI Backend
 │
 ├── OpenCV Image Processing
 │
 ├── Librosa Audio Processing
 │
 ├── Feature Extraction
 │
 └── Machine Learning Models
 │
 ▼
Prediction Engine
 │
 ▼
Diagnostic Report
```

---

## 🛠️ Technology Stack

### Frontend

- React.js
- Vite
- Tailwind CSS
- Framer Motion
- Lucide React

### Backend

- FastAPI
- Python
- OpenCV
- NumPy
- Pandas
- Librosa
- Scikit-Learn

### Authentication

- Google OAuth

### Machine Learning

- Computer Vision Model
- Voice Biomarker Model
- Feature Engineering Pipeline

---

## 📸 Application Screenshots

### Landing Page

![Landing Page](images/landing-page.png)

---

### Google Authentication

![Google Authentication](images/google-auth.png)

---

### Dashboard

![Dashboard](images/dashboard.png)

---

### Assessment Initialization

![Initialization](images/initializing.png)

---

### Diagnostic Procedure

![Procedure Start](images/procedure-start.png)

---

### Motor Analysis Upload

![Motor Upload](images/motor-upload.png)

---

### Image Processing

![Image Processing](images/image-processing.png)

---

### Audio Analysis

![Audio Processing](images/audio-processing.png)

---

### Final Diagnostic Report

![Diagnostic Report](images/diagnostic-report.png)

---

## 📂 Project Structure

```text
parkinsons-disease-main/
│
├── backend/
│   ├── datasets/
│   ├── api.py
│   ├── auth.py
│   ├── feature_extraction.py
│   ├── train_images.py
│   ├── train_voice.py
│   ├── models.py
│   ├── utils.py
│   └── requirements.txt
│
├── public/
│
├── src/
│   ├── components/
│   ├── pages/
│   ├── App.jsx
│   └── main.jsx
│
├── images/
│
└── README.md
```

---

## 🚀 Installation

### Clone Repository

```bash
git clone https://github.com/ZoohaFatima/parkinsons-disease-prediction.git
```

```bash
cd parkinsons-disease-prediction
```

---

### Backend Setup

```bash
cd backend
```

Create virtual environment:

```bash
python -m venv myenv
```

Activate environment:

Windows:

```bash
myenv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Start backend server:

```bash
run_server.bat
```

Backend runs on:

```text
http://127.0.0.1:8000
```

---

### Frontend Setup

Open another terminal:

```bash
npm install
```

Run React application:

```bash
npm run dev
```

Frontend runs on:

```text
http://localhost:5173
```

---

## 🔬 Machine Learning Pipeline

### Image Analysis Pipeline

1. Upload Spiral Drawing
2. Image Preprocessing
3. Feature Extraction
4. Model Prediction
5. Confidence Calculation

### Voice Analysis Pipeline

1. Upload Voice Sample
2. Audio Preprocessing
3. Feature Extraction
4. Model Prediction
5. Confidence Calculation

### Final Assessment

- Motor Analysis Score
- Voice Analysis Score
- Combined Prediction
- Diagnostic Report

---

## 📊 Dataset

The project uses publicly available Parkinson's Disease datasets including:

### Spiral Drawings
- Healthy Subjects
- Parkinson's Patients

### Voice Recordings
- Healthy Voice Samples
- Parkinson's Voice Samples

---

## ⚠ Disclaimer

This application is intended for educational, research, and demonstration purposes only.

It is not a substitute for professional medical diagnosis or treatment.

Always consult qualified healthcare professionals for medical advice.

---

## 👩‍💻 Author

**Zuha Fatima**

Electronics and Communication Engineering

Brain-Computer Interface and AI Research Enthusiast

---

## ⭐ Future Improvements

- EEG-based Analysis
- Real-Time Voice Recording
- Cloud Deployment
- Advanced Deep Learning Models
- Mobile Application
- Multi-Language Support

---

## 📜 License

This project is licensed under the MIT License.
B --> C[Feature Selection]
C --> D[Model Training]
D --> E[Model Evaluation]
E --> F[Prediction Output]
