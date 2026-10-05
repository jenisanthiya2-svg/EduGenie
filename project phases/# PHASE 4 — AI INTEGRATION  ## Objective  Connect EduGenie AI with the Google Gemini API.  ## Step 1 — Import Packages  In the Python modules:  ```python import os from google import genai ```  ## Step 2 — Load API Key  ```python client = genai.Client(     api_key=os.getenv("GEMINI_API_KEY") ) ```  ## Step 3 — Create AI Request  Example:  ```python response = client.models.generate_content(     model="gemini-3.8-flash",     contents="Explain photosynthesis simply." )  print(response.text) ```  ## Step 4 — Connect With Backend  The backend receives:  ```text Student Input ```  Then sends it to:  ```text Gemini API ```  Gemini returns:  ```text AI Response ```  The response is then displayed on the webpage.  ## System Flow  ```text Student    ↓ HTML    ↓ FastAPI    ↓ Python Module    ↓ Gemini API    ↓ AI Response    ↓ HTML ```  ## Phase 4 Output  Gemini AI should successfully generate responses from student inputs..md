# PHASE 4 — AI INTEGRATION

## Objective

Connect EduGenie AI with the Google Gemini API.

## Step 1 — Import Packages

In the Python modules:

```python
import os
from google import genai
```

## Step 2 — Load API Key

```python
client = genai.Client(
    api_key=os.getenv("GEMINI_API_KEY")
)
```

## Step 3 — Create AI Request

Example:

```python
response = client.models.generate_content(
    model="gemini-3.8-flash",
    contents="Explain photosynthesis simply."
)

print(response.text)
```

## Step 4 — Connect With Backend

The backend receives:

```text
Student Input
```

Then sends it to:

```text
Gemini API
```

Gemini returns:

```text
AI Response
```

The response is then displayed on the webpage.

## System Flow

```text
Student
   ↓
HTML
   ↓
FastAPI
   ↓
Python Module
   ↓
Gemini API
   ↓
AI Response
   ↓
HTML
```

## Phase 4 Output

Gemini AI should successfully generate responses from student inputs.
