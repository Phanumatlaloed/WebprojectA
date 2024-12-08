FROM python:3.12

WORKDIR /myproject

COPY . .

RUN pip install django

RUN python manage.py migrate

EXPOSE 8888

CMD ["python", "manage.py", "runserver", "0.0.0.0:8888"]
