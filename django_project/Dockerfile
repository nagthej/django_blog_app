# Install the base requirements for the app.
# This stage is to support development.

FROM python:3

WORKDIR /app

ADD . /app

RUN pip install -r requirements.txt

EXPOSE 8000

CMD ["python", "/app/manage.py", "runserver", "0.0.0.0:8000"]

