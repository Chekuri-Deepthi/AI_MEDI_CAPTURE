# 🩺 AI-Powered Medical Text Digitization & EMR Integration

## 📌 Project Overview
This project is an AI-powered mobile application designed to digitize doctors’ handwritten notes and prescriptions using OCR (Optical Character Recognition) and Vision GPT-based handwriting recognition.

The extracted text is processed using Natural Language Processing (NLP) techniques and integrated into Electronic Medical Record (EMR) systems using FHIR API / HL7 Protocol standards.

The application aims to reduce manual data entry, improve medical documentation accuracy, and streamline hospital workflows.

---

# 🚀 Features

✅ Handwritten Prescription Recognition  
✅ AI-based OCR Text Extraction  
✅ Vision GPT Integration  
✅ Medical Text Processing using NLP  
✅ EMR Integration using FHIR API  
✅ Secure Authentication System  
✅ Mobile App using Flutter  
✅ FastAPI Backend Services  
✅ Real-Time OCR Processing  
✅ Upload from Camera & Gallery  
✅ Structured Medical Record Generation  

---

# 🛠️ Technology Stack

## 📱 Frontend (Mobile App)
- Flutter
- Dart
- Provider / Riverpod
- HTTP Package
- Image Picker

## 🖥️ Backend
- FastAPI
- Python
- Uvicorn

## 🤖 AI & OCR
- Tesseract OCR
- Vision GPT (TrOCR)
- PyTorch
- Transformers
- OpenCV

## 🧠 NLP
- spaCy
- TextBlob
- Transformers

## 🏥 EMR Integration
- FHIR API
- HL7 Protocol

## 🗄️ Database
- PostgreSQL / Firebase

---

# 📂 Project Structure

```bash
ai_ocr_emr_project/
│
├── mobile_app/
│   ├── lib/
│   │   ├── screens/
│   │   ├── services/
│   │   ├── providers/
│   │   ├── widgets/
│   │   ├── models/
│   │   ├── utils/
│   │   └── main.dart
│   ├── assets/
│   └── pubspec.yaml
│
├── backend_ai/
│   ├── models/
│   ├── services/
│   ├── routes/
│   ├── utils/
│   ├── app.py
│   ├── config.py
│   └── requirements.txt
│
├── dataset/
├── README.md
└── .env




# ⚙️ Installation Guide

## 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
```

---

# 2️⃣ Backend Setup

## Install Dependencies

```bash
cd backend_ai
pip install -r requirements.txt
```

## Run Backend Server

```bash
uvicorn app:app --reload
```

Backend will run on:

```bash
http://127.0.0.1:8000
```

API Documentation:

```bash
http://127.0.0.1:8000/docs
```

---

# 3️⃣ Flutter App Setup

## Install Flutter Packages

```bash
cd mobile_app
flutter pub get
```

## Run Flutter App

```bash
flutter run
```

---

# 🤖 OCR Workflow

1. User uploads handwritten prescription image  
2. Image preprocessing using OpenCV  
3. OCR extraction using Tesseract / Vision GPT  
4. NLP correction of extracted text  
5. Structured medical text generation  
6. Integration with EMR system using FHIR API  

---

# 🔗 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/extract_text` | Extract handwritten text |
| POST | `/store_ocr_text` | Store OCR text in EMR |
| GET | `/get_patient/{id}` | Fetch patient details |
| GET | `/get_observations/{id}` | Fetch EMR observations |

---

# 🔒 Security Features

- JWT Authentication  
- Password Hashing using bcrypt  
- Environment Variable Protection  
- Secure API Communication  

---

# 📸 Screenshots

Add screenshots of:

- Login Screen  
- Upload Screen  
- OCR Result Screen  
- EMR Integration Screen  

---

# 📈 Expected Outcome

- Faster medical documentation  
- Reduced manual data entry errors  
- Improved accessibility of patient records  
- Efficient EMR integration  
- Better healthcare workflow automation  

---

# 👨‍💻 Team Members

| Name | Role |
|------|------|
| Member 1 | AI/ML Development |
| Member 2 | Backend Development |
| Member 3 | Flutter Mobile App |
| Member 4 | Testing & Documentation |

---

# 📚 Future Enhancements

- Multi-language handwriting recognition  
- Voice-to-text integration  
- Offline OCR support  
- Cloud deployment  
- AI-powered prescription validation  

---

# 📜 License

This project is developed for educational and research purposes.

---

# 🙌 Acknowledgements

- FastAPI  
- Flutter  
- PyTorch  
- Hugging Face Transformers  
- Tesseract OCR  
- FHIR Standards  

---

# ⭐ Support

If you like this project, give it a ⭐ on GitHub!
Flutter
PyTorch
Hugging Face Transformers
Tesseract OCR
FHIR Standards

