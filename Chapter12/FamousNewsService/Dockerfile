FROM python:latest

COPY . /app

WORKDIR /app

RUN pip install -r requirements.txt

ENTRYPOINT ["nameko"]

CMD ["run", "--config",  "config.yaml", "service"]

EXPOSE 8000
