# 🎓 SETU
### AI-Powered College Helpdesk Chatbot for JECRC Foundation

🚀 **Live Demo:** https://jecrc-foundation-helpdesk.onrender.com/

💬 **English | हिन्दी | Hinglish Support**

---

## 📖 Overview

SETU is an AI-powered college helpdesk chatbot developed by **Daksh** to simplify access to college-related information for students, parents, and aspirants.

The chatbot provides instant answers related to admissions, fees, hostel facilities, academics, placements, campus life, events, scholarships, and much more through a simple conversational interface.

Designed specifically for **JECRC Foundation**, SETU acts as a bridge between students and college information by making important details accessible anytime, anywhere.

---

## ✨ Features

### 💬 Smart AI Chatbot
- Instant responses to student queries
- Context-aware conversations
- Follow-up question handling
- Hybrid AI-based intent classification

### 🌍 Multilingual Support
- English support
- Hindi support
- Hinglish support

### 🧠 Intelligent NLP Engine
- TF-IDF + Cosine Similarity matching
- Keyword-based classification
- Typo correction using Levenshtein Distance
- Automatic language detection

### 📚 Comprehensive Knowledge Base
- 154+ intents
- 900+ training patterns
- Covers almost every major college-related topic

### 📊 Admin Dashboard
- Chat analytics
- Query monitoring
- Unresolved query management
- CSV/PDF export support
- Real-time statistics and charts

### 🔒 Security Features
- Rate limiting
- Input sanitization
- Admin authentication
- Environment variable protection
- Automatic old-data cleanup

### 📱 Responsive Design
- Mobile-friendly UI
- Desktop support
- Fast and lightweight interface

---

## 🏫 Topics Covered

| Category | Coverage |
|-----------|-----------|
| Admissions | Eligibility, Documents, REAP, JEE, Deadlines |
| Departments | CSE, IT, ECE, EE, ME, CE, AI & DS |
| Fees | Structure, Scholarships, Refunds |
| Placements | Companies, Packages, Training |
| Hostel | Facilities, Rules, Mess, Visitors |
| Academics | Exams, Attendance, Results, Credits |
| Campus Life | Library, Sports, Wi-Fi, Medical |
| Events & Clubs | Renaissance, TEDx, NSS, Technical Events |
| Safety | Anti-Ragging, Counselling, Complaints |
| Others | Faculty, Alumni, Contacts, Brochures |

---

## ⚙️ How It Works

When a user asks a question:

1. User query is cleaned and normalized.
2. Common spelling mistakes are corrected.
3. Language (English/Hindi/Hinglish) is detected.
4. Previous conversation context is checked.
5. TF-IDF similarity matching is performed.
6. Keyword matching is used as a fallback.
7. Best intent is selected.
8. Appropriate response is generated.
9. Relevant links are attached.
10. Query is stored for analytics.

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

### Database
- SQLite

### Frontend
- HTML
- CSS
- JavaScript

### Additional Tools
- BeautifulSoup4
- FPDF2
- gTTS
- AssemblyAI API

---

## 📂 Project Structure

```text
college_chatbot/
│
├── app.py
├── chatbot_engine.py
├── database.py
├── config.py
├── web_scraper.py
├── intents.json
├── requirements.txt
│
├── templates/
│
└── static/
```

---

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
python app.py
```

Open:

```text
http://127.0.0.1:5000
```

---

## 📈 Performance

| Metric | Value |
|----------|----------|
| Overall Accuracy | 85–90% |
| Exact Match Accuracy | ~95% |
| Hybrid Model Accuracy | ~92% |
| Hindi Detection Accuracy | >90% |
| Average Response Time | <1 Second |

---

## 🎯 Problem Solved

✔ Information scattered across multiple webpages

✔ Repetitive student queries

✔ Limited office timings

✔ Busy admission helplines

✔ Language barriers for Hindi-speaking students

✔ Delayed access to important information

---

## 🔮 Future Improvements

- ChatGPT/Gemini fallback integration
- WhatsApp chatbot deployment
- ERP integration
- Mobile application
- Self-learning capabilities
- BERT-based intent classification
- Regional language support
- Sentiment analysis
- Document understanding and processing

---

## 👨‍💻 Developer

### Daksh

B.Tech Computer Science & Engineering  
JECRC Foundation, Jaipur

---

## 🌐 Try It Live

### https://jecrc-foundation-helpdesk.onrender.com/

If you'd like to test the chatbot yourself, simply open the link above and start chatting.

---

## ⭐ Support

If you found this project useful, consider giving the repository a **Star ⭐**.

Feedback, suggestions, and contributions are always welcome.
