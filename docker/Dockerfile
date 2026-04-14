FROM python:3.11-slim

WORKDIR /App

COPY App/requirements.txt .

RUN pip install --no-cache-dir -r requirements.txt

COPY App/ .

CMD ["python", "app.py"]
