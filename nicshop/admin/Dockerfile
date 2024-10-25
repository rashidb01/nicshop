FROM python:3.12.6

WORKDIR /app

COPY requirements.txt .
RUN pip install -r requirements.txt

COPY nicshop/ .

EXPOSE 8000

# Команда запуска Django админки
CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]
