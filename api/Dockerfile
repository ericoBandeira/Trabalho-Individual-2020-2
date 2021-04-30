FROM python:3.9.0

RUN pip3 install djangorestframework django-cors-headers pylint psycopg2

WORKDIR /rest

COPY . .

CMD python3 manage.py migrate && python3 manage.py runserver 0.0.0.0:8000