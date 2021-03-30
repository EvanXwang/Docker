FROM python:3.8

WORKDIR /var/app

COPY . .

RUN pip3 install -r requirements.txt

CMD ["python3", "./manage.py", "runserver", "0.0.0.0:8000", "--noreload"]
