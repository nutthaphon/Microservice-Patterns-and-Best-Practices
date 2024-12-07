FROM python:3.14.0a2

COPY . /app

WORKDIR /app

RUN pip install -r requirements.txt

ENTRYPOINT ["nameko"]

CMD ["run", "--config",  "config.yaml", "service"]

EXPOSE 8000
