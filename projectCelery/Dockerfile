FROM python:3.11.4-alpine

WORKDIR /usr/src/app

ENV PYTHONDONTWRITEBYTECODE 1
ENV PYHTONBUFFERED 1

RUN pip install --upgrade pip
COPY ./requirments.txt /usr/src/app/requirments.txt
RUN pip install -r requirments.txt