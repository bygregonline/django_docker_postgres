FROM python:3.7.2-alpine3.9
RUN mkdir -p /usr/src/django
RUN apk add musl-dev
RUN apk add gcc
RUN apk  add postgresql-dev
RUN apk  add postgresql
RUN apk add  g++
RUN apk add libxml2
RUN apk add libxml2-dev
RUN apk add linux-headers
RUN apk add libxslt-dev 
WORKDIR /usr/src/django
COPY ./requirements.txt /usr/src/django/
RUN pip install --no-cache-dir -r requirements.txt

