# EduGenie
# 🎓 EduGenie AI

## AI-Powered Personalized Learning Assistant

EduGenie AI is an AI-powered personalized learning assistant designed to help students understand concepts, ask questions, practice through quizzes, summarize study materials, and follow a structured learning path.

---

## 🎯 Objectives

* Provide simple explanations for difficult topics.
* Answer students' academic questions.
* Generate topic-based quizzes.
* Summarize lengthy study materials.
* Create personalized learning paths.
* Make learning simple, interactive, and personalized.

---

## 🛠️ Technologies Used

### Frontend

* HTML5
* CSS3
* Jinja2

### Backend

* Python
* FastAPI
* Uvicorn

### AI

* Google Gemini API
* Google GenAI SDK

### Tools

* Visual Studio Code
* Git
* GitHub
* Python Virtual Environment

---

## 📂 Project Structure

```text
EduGenie-AI/
│
├── static/
│   └── style.css
│
├── templates/
│   └── index.html
│
├── main.py
├── explanation_module.py
├── qna.py
├── quiz_module.py
├── summary_module.py
├── learning_path.py
│
├── requirements.txt
├── .env
├── .gitignore
└── README.md
```

---

## 🚀 Main Features

### 1. Topic Explanation

Explains difficult topics in a simple and understandable way.

### 2. Question & Answer

Allows students to ask questions and receive AI-generated answers.

### 3. Quiz Generation

Generates multiple-choice questions for practice.

### 4. Summarization

Converts lengthy study material into short notes.

### 5. Personalized Learning Path

Creates a structured learning path based on the selected topic.

---

## 🔄 System Flow

```text
Student
   ↓
Frontend
   ↓
FastAPI Backend
   ↓
Gemini AI
   ↓
AI Processing
   ↓
Generated Response
   ↓
Student
```

---

## ⚙️ Installation

Create a virtual environment:

```bash
python -m venv venv
```

Activate it:

```bash
venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 🔑 API Configuration

Create a `.env` file:

```env
GEMINI_API_KEY=your_api_key_here
```

Do not upload the `.env` file to GitHub.

---

## ▶️ Run the Project

Run:

```bash
uvicorn main:app --reload
```

Open:

```text
http://127.0.0.1:8000
```

---

## 📌 Development Phases

1. Project Setup
2. Frontend Development
3. Backend Development
4. AI Integration
5. Learning Modules
6. Personalization
7. Testing & Error Handling
8. Documentation & Deployment

---

## 🔮 Future Enhancements

* Student login
* User profiles
* Progress tracking
* PDF upload
* Voice-based learning
* Flashcard generation
* Performance analytics
* Database integration
* Mobile application
* Cloud deployment

---

## 🎓 Learning Outcomes

This project provides practical experience in:

* Python
* FastAPI
* Frontend development
* Backend development
* API integration
* AI integration
* Prompt engineering
* Git and GitHub
* Software testing
* Project documentation

---

## 📄 Project Status

```text
Phase 1  → Project Setup
Phase 2  → Frontend Development
Phase 3  → Backend Development
Phase 4  → AI Integration
Phase 5  → Learning Modules
Phase 6  → Personalization
Phase 7  → Testing
Phase 8  → Documentation & Deployment
```

---

## 📜 License

This project is developed for educational purposes.
