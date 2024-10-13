pip install fastapi uvicorn
pip freeze > requirements.txt
uvicorn main:app --reload

http://127.0.0.1:8000/docs
http://127.0.0.1:8000/redoc

