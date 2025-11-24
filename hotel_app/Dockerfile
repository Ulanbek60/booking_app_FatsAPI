FROM python:3.12

ENV PYTHONUNBUFFERED=1

WORKDIR /hotel_app

COPY req.txt /hotel_app/

RUN pip install --upgrade pip && \
    pip install -r req.txt


COPY . /hotel_app/
