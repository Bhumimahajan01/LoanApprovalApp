FROM python:3.11-slim
# start with linux + python 3.11

WORKDIR /app
#create working location /app

COPY requirements.txt .

RUN pip install --no-cache-dir -r requirements.txt

COPY . .