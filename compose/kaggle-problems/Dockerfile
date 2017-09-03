FROM python:3.6
MAINTAINER arineto30@gmail.com

ENV PYTHONUNBUFFERED 1

RUN apt-get -y update

COPY ./requirements.txt /requirements.txt
RUN pip install -r /requirements.txt

WORKDIR /app
