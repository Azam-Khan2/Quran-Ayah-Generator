# === README.md ===
# Daily Quran Ayah API
A simple Python API that returns a random ayah from the Quran.

## How to Run

### 1. Local (without Docker)
```bash
pip install -r requirements.txt  # Install dependencies
uvicorn app.main:app --reload  # Start FastAPI dev server
```
Visit `http://127.0.0.1:8000/`