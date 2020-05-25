FROM python:3.7-slim

WORKDIR /app

COPY . /app

RUN pip install gensim

EXPOSE 80

ENV NAME World

CMD ["python", "hello.py"]
