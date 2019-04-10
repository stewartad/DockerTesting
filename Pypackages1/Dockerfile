FROM python:3.7-slim

WORKDIR /app

COPY . /app

RUN pip install --trusted-host pypi.python.org -r requirements.txt

ENV NAME World

CMD ["python", "app.py"]