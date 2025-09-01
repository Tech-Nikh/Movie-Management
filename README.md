# Movie-Management
This project creates a Movie Management API that supports all CRUD operations, includes pagination, has configuration based on the environment, features unit and integration tests, and provides Swagger documentation.

# Tech Stack

1)Language: Python 3.12.5

2)Web Framework: FastAPI

3)ASGI Server: Uvicorn

4)ORM: SQLAlchemy

5)Validation / Schemas: Pydantic

6)Database: SQLite (file: movies.db)

7)Testing: pytest, FastAPI TestClient

Getting Started
 1) Clone & set up a virtual environment
   # Clone
git clone <your-repo-url>
cd <your-repo-folder>

# On Windows (PowerShell)
py -m venv .venv
.\.venv\Scripts\Activate.ps1

2) Install dependencies
   pip install -r requirements.txt
   
3) Run the API
   uvicorn main:app --reload
   
i)API will start at: http://127.0.0.1:8000/

ii)Interactive docs (Swagger): http://127.0.0.1:8000/docs

iii)ReDoc: http://127.0.0.1:8000/redoc

The SQLite database file movies.db will be created automatically on first run.


 
