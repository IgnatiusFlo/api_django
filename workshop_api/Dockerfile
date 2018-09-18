FROM python:3.6

ENV PYTHONUNBUFFERED 1
ENV DJANGO_ENV dev
ENV DOCKER_CONTAINER 1

COPY ./requi.txt /code/requi.txt
RUN pip install -r /code/requi.txt

COPY . /code/
WORKDIR /code/

EXPOSE 8000

