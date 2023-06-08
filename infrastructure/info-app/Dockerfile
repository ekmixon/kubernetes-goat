FROM python:3-alpine3.18
LABEL MAINTAINER="Madhu Akula" INFO="Kubernetes Goat"

COPY app.py /app.py

RUN pip install flask

EXPOSE 5000

CMD [ "python", "/app.py" ]
