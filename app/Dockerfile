FROM python:3.5.2

RUN apt-get update
RUN apt-get -y install mysql-client

# for caravel
RUN apt-get install build-essential libssl-dev libffi-dev python-dev python-pip libsasl2-dev libldap2-dev

RUN pip install --upgrade pip

RUN pip install caravel
