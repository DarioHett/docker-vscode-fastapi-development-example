FROM python:3.10

RUN mkdir /app

COPY requirements.txt /app

WORKDIR /app

RUN pip install -r requirements.txt 

COPY . /app

EXPOSE 8000

CMD uvicorn app.main:app --reload --host 0.0.0.0 --port 8000