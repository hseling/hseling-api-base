FROM tiangolo/uwsgi-nginx-flask:python3.6-alpine3.7

LABEL maintainer="Sergey Sobko <ssobko@hse.ru>"

COPY ./requirements.txt /requirements.txt

RUN apk add --update --no-cache g++ gcc libxslt-dev
RUN pip install -r /requirements.txt
