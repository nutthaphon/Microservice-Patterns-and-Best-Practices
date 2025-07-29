FROM python:3.14.0rc1 
COPY . /app 
WORKDIR /app 
RUN pip install setuptools==45
RUN pip install -r requirements.txt 
ENTRYPOINT ["python"] 
CMD ["app.py"] 
EXPOSE 5000 