<<<<<<< HEAD
FROM python:3.9-slim
=======
FROM python:3.9
>>>>>>> 62a913c (Initial commit)

WORKDIR /app

RUN pip install gunicorn==20.1.0

<<<<<<< HEAD
COPY requirements.txt ./
=======
COPY requirements.txt .
>>>>>>> 62a913c (Initial commit)

RUN pip install -r requirements.txt --no-cache-dir

COPY . .

CMD ["gunicorn", "--bind", "0.0.0.0:8000", "backend.wsgi"]
