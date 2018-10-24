FROM tiangolo/uwsgi-nginx-flask:python3.7

LABEL maintainer="Sergey Sobko <ssobko@hse.ru>"

COPY ./requirements.txt /requirements.txt

RUN apt-get install -y g++ gcc libxml2-dev libxslt1-dev
RUN pip install -r /requirements.txt
