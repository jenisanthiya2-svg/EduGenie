# PHASE 1 — PROJECT SETUP

## Objective

Set up the complete development environment required for the EduGenie AI project.

## Step 1 — Create Project

Create a folder:

```text
EduGenie-AI
```

Open the folder in VS Code.

## Step 2 — Open Terminal

In VS Code:

```text
Terminal → New Terminal
```

## Step 3 — Create Virtual Environment

```bash
python -m venv venv
```

Activate:

```bash
venv\Scripts\activate
```

## Step 4 — Install Packages

```bash
pip install fastapi uvicorn jinja2 python-dotenv google-genai python-multipart
```

## Step 5 — Create Files

Create:

```text
main.py
explanation_module.py
qna.py
quiz_module.py
summary_module.py
learning_path.py
requirements.txt
.env
.gitignore
README.md
```

Create folders:

```text
static/
templates/
```

## Step 6 — requirements.txt

Run:

```bash
pip freeze > requirements.txt
```

## Step 7 — .gitignore

Add:

```text
venv/
.env
__pycache__/
*.pyc
```

## Step 8 — .env

Add:

```env
GEMINI_API_KEY=your_api_key_here
```

## Expected Structure

```text
EduGenie-AI/
│
├── static/
├── templates/
├── venv/
├── .env
├── .gitignore
├── main.py
├── explanation_module.py
├── qna.py
├── quiz_module.py
├── summary_module.py
├── learning_path.py
├── requirements.txt
└── README.md
```

## Phase 1 Output

At the end of Phase 1:

* Project folder created
* Virtual environment created
* Required packages installed
* Project files created
* API key configured
* Git ignore configured
