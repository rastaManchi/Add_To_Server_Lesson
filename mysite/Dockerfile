FROM python:3.10

WORKDIR /app

RUN apt-get update

RUN pip3 install --upgrade pip
COPY ../requirements.txt .
RUN pip3 install -r requirements.txt

COPY . .

CMD python manage.py runserver 0.0.0.0:8000