FROM python:3.11-alpine

WORKDIR /app

COPY app.py requirements.txt /app/

RUN pip install -r requirements.txt

EXPOSE 5000

CMD ["python3", "-m", "flask", "run", "--host=0.0.0.0"]