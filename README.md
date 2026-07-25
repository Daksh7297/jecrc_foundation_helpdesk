# 🎓 SETU
### AI-Powered College Helpdesk Chatbot for JECRC Foundation

🚀 **Live Demo:** https://setu-2cn0.onrender.com/

💬 **English | हिन्दी | Hinglish Support**

---

## 📖 Overview

SETU is an AI-powered college helpdesk chatbot developed for **JECRC Foundation** to simplify access to college-related information for students, parents, and aspirants.

Instead of searching multiple webpages or visiting different offices, users can simply ask questions in natural language and receive instant responses. The chatbot supports English, Hindi, and Hinglish, making it accessible to a wider audience.

Using Natural Language Processing (NLP) and hybrid intent classification, SETU can answer questions related to admissions, departments, fees, scholarships, placements, hostel facilities, academics, campus life, faculty, and many other college services.

---

## ❗ Problem Statement

Students frequently face challenges while searching for accurate college information because:

- Information is scattered across multiple webpages
- Office timings are limited
- Admission helplines remain busy
- Students repeatedly ask the same questions
- Hindi-medium students struggle with English-only information
- Finding faculty and department information takes time

SETU solves these problems by providing instant, AI-powered assistance 24×7.

---

## ✨ Features

### 🤖 AI Chatbot
- Instant AI-powered responses
- Natural conversation flow
- Context-aware follow-up support
- Intelligent intent recognition
- Hybrid NLP model

### 🌍 Multilingual Support
- English
- Hindi
- Hinglish
- Automatic language detection

### 🧠 Smart NLP Engine
- TF-IDF Vectorization
- Cosine Similarity
- Keyword Matching
- Context Handling
- Confidence Scoring
- Automatic Typo Correction
- 230+ spelling corrections
- 3000+ vocabulary words

### 🎤 Voice Assistant
- Voice-to-Text using AssemblyAI
- Text-to-Speech using Google TTS
- Microsoft Edge TTS support
- Voice conversation support

### 📚 Knowledge Base
- 203 College Intents
- 8,883+ Training Patterns
- 2,252 Auto-generated Keywords
- 265 Faculty Members
- 9 Academic Departments
- English & Hindi Responses for every intent

### 🏫 Covers Information About

- Admission Process
- Eligibility
- Required Documents
- REAP Counselling
- Fee Structure
- Scholarships
- Hostel Facilities
- Hostel Rules
- Departments
- Faculty Details
- Placements
- Companies
- Internship Opportunities
- Academic Calendar
- Examination Rules
- Attendance
- RTU Information
- Campus Life
- Clubs
- Sports
- Library
- Medical Facilities
- Transport
- Parking
- Wi-Fi
- Anti Ragging
- Student Support
- Emergency Contacts
- Rankings
- Recognition
- Campus Facilities

...and much more.

---

## 📊 Admin Dashboard

The chatbot includes a complete admin portal featuring:

- Secure Login
- Real-time Chat Monitoring
- Daily & Weekly Analytics
- Interactive Charts
- Recent Chat History
- Topic Distribution
- Confidence Analysis
- Unresolved Query Tracking
- CSV Export
- PDF Report Generation
- Usage Statistics

---

## 🔒 Security Features

- Rate Limiting
- Input Sanitization
- Secure Admin Authentication
- Environment Variables
- Automatic Chat Cleanup
- Protected API Keys

---

## ⚙️ AI Workflow

When a user asks a question:

1. User query is cleaned and normalized.
2. Common spelling mistakes are corrected.
3. Language is automatically detected.
4. TF-IDF Vectorization is performed.
5. Cosine Similarity score is calculated.
6. Keyword Matching improves confidence.
7. Best matching intent is selected.
8. Response is returned in the user's language.
9. Chat history is stored for analytics.

---

## 🛠️ Tech Stack

### Backend
- Python
- Flask

### AI / NLP
- Scikit-Learn
- TF-IDF Vectorization
- Cosine Similarity
- NLTK
- RapidFuzz

### Database
- SQLite

### Frontend
- HTML
- CSS
- JavaScript

### Voice AI
- AssemblyAI
- Google TTS
- Microsoft Edge TTS

### Other Libraries
- BeautifulSoup4
- Requests
- FPDF2

### Deployment
- Render
- GitHub

---

## 📂 Project Structure

```text
college_chatbot/
│
├── app.py
├── chatbot_engine.py
├── database.py
├── config.py
├── faculty_db.py
├── faculty_data.json
├── intentsupdated.json
├── web_scraper.py
├── requirements.txt
├── render.yaml
├── Procfile
├── api.env
├── chat_history.db
│
├── templates/
│   ├── index.html
│   ├── admin.html
│   ├── admin_login.html
│   └── chatbot_widget.html
│
├── static/
│   ├── css/
│   ├── js/
│   └── images/
```

## 🚀 Installation

```bash
git clone https://github.com/heydaksh7297/Setu.git
cd Setu

pip install -r requirements.txt

python app.py
```

Open

```
http://127.0.0.1:5000
```

---

## 📈 Performance

| Metric | Value |
|----------|----------:|
| Total Intents | 203 |
| Training Patterns | 8,883+ |
| Faculty Records | 265 |
| Departments | 9 |
| Auto Keywords | 2,252 |
| Typo Corrections | 230+ |
| Vocabulary Size | 3,000+ |
| Overall Accuracy | 85–90% |
| Exact Match Accuracy | ~95% |
| Hybrid Model Accuracy | ~92% |
| Hindi Detection Accuracy | >90% |
| Average Response Time | <1 Second |

---

## 🎯 Applications

- Student Helpdesk
- College Information System
- Admission Support
- Faculty Information Portal
- Campus Assistant
- FAQ Automation
- Student Query Resolution
- Educational Institutions

---

## 🔮 Future Scope

- ChatGPT/Gemini Integration
- WhatsApp Chatbot
- ERP Integration
- Android & iOS App
- Self-learning AI
- BERT-based Intent Detection
- Multi-college Support
- Regional Language Support
- Website Widget
- Sentiment Analysis
- Document Processing

---

## 👨‍💻 Developer

**Daksh**

B.Tech Computer Science & Engineering

JECRC Foundation, Jaipur

---

## 🌐 Live Demo

https://setu-2cn0.onrender.com/

---

## ⭐ Support

If you found this project useful, please consider giving it a **Star ⭐**.

Contributions, suggestions, and feedback are always welcome.
