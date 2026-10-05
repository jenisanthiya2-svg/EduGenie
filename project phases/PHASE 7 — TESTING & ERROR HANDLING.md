# PHASE 7 — TESTING & ERROR HANDLING

## Objective

Test the complete EduGenie application and identify errors.

## Test 1 — Homepage

Check:

```text
http://127.0.0.1:8000
```

Expected:

```text
EduGenie homepage loads successfully.
```

## Test 2 — Explanation

Input:

```text
Photosynthesis
```

Expected:

```text
AI generates an explanation.
```

## Test 3 — Q&A

Input:

```text
What is a variable in Python?
```

Expected:

```text
AI provides an answer.
```

## Test 4 — Quiz

Input:

```text
Python
```

Expected:

```text
Quiz questions are generated.
```

## Test 5 — Summary

Input:

```text
Long study material
```

Expected:

```text
Short summary is generated.
```

## Test 6 — Learning Path

Input:

```text
Web Development
```

Expected:

```text
Structured learning path is generated.
```

## Error Handling

Check:

* Empty input
* Invalid input
* Missing API key
* Gemini API error
* Server error
* Network error

## Testing Checklist

```text
☐ Homepage
☐ Explanation
☐ Q&A
☐ Quiz
☐ Summary
☐ Learning Path
☐ Empty input
☐ API error
☐ Server error
```

## Phase 7 Output

All major features should work correctly without crashing the application.
