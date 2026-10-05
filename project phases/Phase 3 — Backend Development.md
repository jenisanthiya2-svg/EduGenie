# PHASE 3 — BACKEND DEVELOPMENT

## Objective

Build the backend using Python and FastAPI.

## Step 1 — Open main.py

Add:

```python
from fastapi import FastAPI, Request, Form
from fastapi.responses import HTMLResponse
from fastapi.templating import Jinja2Templates

app = FastAPI()

templates = Jinja2Templates(
    directory="templates"
)
```

## Step 2 — Home Route

```python
@app.get("/", response_class=HTMLResponse)
async def home(request: Request):

    return templates.TemplateResponse(
        "index.html",
        {"request": request}
    )
```

## Step 3 — Create Routes

Create routes for:

```text
/explain
/qna
/quiz
/summary
/learning-path
```

Example:

```python
@app.post("/explain")
async def explain(topic: str = Form(...)):

    return {
        "topic": topic
    }
```

## Step 4 — Run Backend

Use:

```bash
uvicorn main:app --reload
```

Open:

```text
http://127.0.0.1:8000
```

## Step 5 — API Documentation

FastAPI automatically provides:

```text
http://127.0.0.1:8000/docs
```

This can be used to test the backend endpoints.

## Expected Flow

```text
HTML Form
    ↓
FastAPI Route
    ↓
Python Function
    ↓
Response
```

## Phase 3 Output

At the end of this phase:

* FastAPI server works
* Homepage loads
* Routes are created
* Frontend connects to backend
