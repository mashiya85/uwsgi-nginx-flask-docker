FROM python:3.9

RUN pip install Flask uwsgi

WORKDIR /app
COPY . /app

CMD ["uwsgi", "--ini", "/app/uwsgi.ini"]
