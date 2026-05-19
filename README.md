# AI Python Code Analyzer

An AI-powered full-stack code analysis platform that analyzes Python files for bugs, code smells, complexity issues, and edge cases.

Built using:
- **FastAPI** for the backend API
- **Next.js + Tailwind CSS** for the frontend
- **Python AST parsing** for static analysis
- **Pytest** integration for generated test execution

---

## Live Demo

https://ai-python-code-analyzer.vercel.app/

---

# Features

- Detects common Python bugs and code smells
- Performs static code analysis using Python AST
- Estimates time complexity of functions
- Generates edge-case pytest tests automatically
- Executes generated tests
- Suggests fixes and improvement strategies
- Upload-and-analyze web interface
- Responsive frontend UI
- REST API powered by FastAPI

---

# Tech Stack

## Frontend
- Next.js
- React
- Tailwind CSS

## Backend
- FastAPI
- Python
- Uvicorn

## Analysis Engine
- Python AST
- Pytest
- Custom workflow orchestration

---

# Example Capabilities

The analyzer can detect issues like:

- Mutable default arguments
- Bare `except` blocks
- Missing return statements
- Unused imports
- Basic complexity estimation
- Edge-case failures

---
## Analyze Python File

### POST `/analyze`

Upload a `.py` file and receive:
- detected bugs
- complexity analysis
- generated tests
- test execution results
- fix suggestions

---

# Why This Project

This project was built to explore:
- AI-assisted developer tooling
- static analysis systems
- automated debugging workflows
- full-stack deployment pipelines
- developer experience tooling
---

# Deployment

## Frontend
Deployed on Vercel.

## Backend
Powered by FastAPI and deployed separately.

---
