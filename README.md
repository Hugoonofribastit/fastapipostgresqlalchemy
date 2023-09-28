python -m venv venv    
.\venv\Scripts\activate
cd app
pip install uvicorn fastapi
pip install sqlalchemy  
pip install psycopg2
uvicorn main:app --reload
# fastapipostgresqlalchemy
