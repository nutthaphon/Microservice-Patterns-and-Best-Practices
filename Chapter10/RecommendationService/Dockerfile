FROM python:3.14.0a3
COPY pip.conf /root/.config/pip/pip.conf
COPY . /app
WORKDIR /app
RUN pip install --upgrade pip
RUN pip install -r requirements.txt
ENTRYPOINT ["nameko"]
CMD ["run", "--config", "config.yaml", "service"]
EXPOSE 5000