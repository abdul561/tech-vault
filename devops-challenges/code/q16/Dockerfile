FROM python:3.8-slim

WORKDIR /app

ADD devops-challenges/code/q16/requirements.txt .

RUN pip install -no-cache-dir -r requirements.txt

ADD . .

WORKDIR /app/devops-challenges/code/q16

CMD ["python", "app.py"]
