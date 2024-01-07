FROM python:3.9-slim

WORKDIR /app

COPY . ./

RUN pip install flask

EXPOSE 5000

ENV FLASK_APP=app.py

CMD [ "python", "app.py","host=127.0.0.1", "port 5000", "FLASK_APP=app.py" ]

