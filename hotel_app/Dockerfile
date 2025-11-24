FROM python:3.12

ENV PYTHONUNBUFFERED=1

WORKDIR /hotel_app

COPY req.txt .x

RUN pip install --upgrade pip && \
    pip install -r req.txt


COPY hotel_app .

CMD ["uvicorn", "8001", "--host", "0.0.0.0", "--port"]
