# Dockerfile
FROM python:3.9-slim

WORKDIR /app
COPY dummy_app.py /app
RUN pip install flask

CMD ["python", "dummy_app.py"]

