# Translation Service

A simple backend service for translations built with **FastAPI** and Python. This project provides endpoints for translating text between languages.  

---

## Features

- REST API for text translation
- FastAPI backend for high performance
- Easy to extend with additional languages or translation engines
- Hot-reloading for development with Uvicorn

---

## Project Structure

00-TRANSLATION-SERVICE-START/
├── main.py # FastAPI entry point
├── .venv/ # Python virtual environment (ignored by Git)
├── requirements.txt # Python dependencies
├── README.md # Project documentation
└── ... # Other source files

---

## Getting Started




### Prerequisites

- Python 3.10+  
- Git  
- Pip (Python package manager)

### Setup

1. **Clone the repository**

```bash
git clone https://github.com/GBracode/translation-service-start.git
cd translation-service-start
```

## Getting Started

2. **Create and activate virtual environment**
python -m venv .venv
.\.venv\Scripts\Activate.ps1   # Windows PowerShell
# or
source .venv/bin/activate       # macOS/Linux

3. **Install dependencies**

pip install -r requirements.txt

4. **Run de application**

uvicorn main:app --reload