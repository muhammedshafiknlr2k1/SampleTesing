A simple **FastAPI-based REST API** to collect candidate resumes, store metadata in memory, and provide filtering/search functionality.

---

## 📂 Folder Structure

- **app/** – Main application code  
  - **main.py** – FastAPI app instance, includes routes  
  - **routes/candidate_routes.py** – API endpoints for candidate operations  
  - **schemas/candidate.py** – Pydantic models for input/output  
  - **services/candidate_service.py** – Business logic for candidates  
  - **utils/file_utils.py** – Functions to save uploaded resumes  
  - **utils/validators.py** – Input validation functions  

- **uploaded_resumes/** – Auto-created folder to store uploaded resumes  
- **requirements.txt** – Python dependencies  
- **README.md** – Project documentation  

> Each file has a single responsibility, following standard FastAPI structure.

---

## 🐍 Python Version

- Python 3.11 (works with 3.10+)

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/miniresume-shafi-s.git
