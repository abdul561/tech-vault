FROM python:3.10-slim

WORKDIR /app

ADD requirements.txt .

RUN pip install -r requirements.txt

ADD . .

CMD ["python", "app.py"]
