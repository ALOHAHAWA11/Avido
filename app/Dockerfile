FROM python:3.11
EXPOSE 8001
ENV PYTHONUNBUFFERED 1

WORKDIR /app
RUN mkdir /app/staticfiles
RUN mkdir /app/mediafiles
COPY . /app

RUN pip install --no-cache-dir -r requirements.txt