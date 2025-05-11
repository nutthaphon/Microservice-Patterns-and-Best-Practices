FROM python:3.12.10 
COPY pip.conf /root/.config/pip/pip.conf
COPY . /app 
WORKDIR /app 
RUN pip install --upgrade pip
RUN pip install -r requirements.txt 
ENTRYPOINT ["nameko"] 
CMD ["run", "--config",  "config.yml", "services"] 
EXPOSE 8000 