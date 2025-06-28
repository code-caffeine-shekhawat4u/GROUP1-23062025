# 🔧 Backend - College Area Detection System

> Backend API and ML model serving infrastructure for the College Area Detection System

---

## 📋 Overview

This backend service handles:

- **🤖 ML Model Serving** - Area classification predictions
- **📸 Image Processing** - Upload and preprocessing pipeline
- **🔗 RESTful APIs** - Frontend communication endpoints
- **💾 Database Management** - Data storage and retrieval
- **🔐 Authentication** - User management and security

---

## 🚀 Quick Start

### Prerequisites

```bash
✅ Python 3.8+
✅ pip (Python package manager)
✅ Virtual environment (recommended)
```

### Installation

```bash
# Create virtual environment
python -m venv venv

# Activate virtual environment
# Windows:
venv\Scripts\activate
# Linux/Mac:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run the server
python app.py
```

---

## 🔗 API Endpoints

| Method | Endpoint       | Description                          |
| ------ | -------------- | ------------------------------------ |
| `POST` | `/api/predict` | Upload image and get area prediction |
| `GET`  | `/api/health`  | Check server health status           |
| `POST` | `/api/upload`  | Upload and store image               |
| `GET`  | `/api/areas`   | Get list of all college areas        |

---

## 👤 Developer

**Karan Choudhary** - Backend Developer

---

## 📝 Notes

- Ensure the ML model is trained and placed in `models/` directory
- Configure database settings in `config/settings.py`
- API documentation available at `/docs` when server is running
