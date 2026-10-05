# PHASE 2 — FRONTEND DEVELOPMENT

## Objective

Create the user interface of EduGenie AI using HTML and CSS.

## Step 1 — Create HTML File

Inside:

```text
templates/
```

create:

```text
index.html
```

## Step 2 — Create CSS File

Inside:

```text
static/
```

create:

```text
style.css
```

## Step 3 — Frontend Sections

The webpage should contain:

```text
EduGenie AI
     ↓
Explain a Topic
     ↓
Ask a Question
     ↓
Generate Quiz
     ↓
Summarize Content
     ↓
Create Learning Path
     ↓
AI Response
```

## Step 4 — HTML

Create forms for:

```html
<form action="/explain" method="post">
```

```html
<form action="/qna" method="post">
```

```html
<form action="/quiz" method="post">
```

```html
<form action="/summary" method="post">
```

```html
<form action="/learning-path" method="post">
```

Each form sends the student's input to the FastAPI backend.

## Step 5 — CSS

Style:

* Main page
* Cards
* Input boxes
* Buttons
* Text areas
* AI response section
* Headings

## Expected Result

The browser should show a clean EduGenie interface containing all five learning features.

## Phase 2 Output

```text
Student
   ↓
Enters information
   ↓
Clicks button
   ↓
Request sent to Backend
```
