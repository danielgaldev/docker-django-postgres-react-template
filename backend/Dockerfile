FROM python:3.7-alpine
RUN apk update && apk add postgresql-dev musl-dev gcc
RUN mkdir /app
WORKDIR /app
COPY requirements.txt /app/
RUN pip install -r requirements.txt
COPY . /app/
