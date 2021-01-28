FROM python:3-slim-stretch

EXPOSE 3001
COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt
ENTRYPOINT python front.py

