FROM python:3.12.6

WORKDIR /app

COPY requirements.txt .
RUN pip install -r requirements.txt

COPY src/ .

EXPOSE 8000

CMD ["python", "app.py"]

