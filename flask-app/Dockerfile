FROM python:3.9-alpine

WORKDIR /flask-app

COPY requirements.txt .

RUN pip install -r requirements.txt

COPY . .

EXPOSE 8080

CMD ["python3", "list.py"]