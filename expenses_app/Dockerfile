From python:3.10.11-slim

ENV TZ="Asia/Kolkata"

RUN apt-get update && apt-get -y upgrade\ 
    && apt-get install -y python3-pip 

COPY requirements.txt /tmp/
RUN pip install -r /tmp/requirements.txt
