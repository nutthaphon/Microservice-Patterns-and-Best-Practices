FROM python:3.13.0b4 
COPY . /app 
WORKDIR /app 
RUN pip install setuptools==45
RUN pip install -r requirements.txt 
ENTRYPOINT ["python"] 
CMD ["app.py"] 
EXPOSE 5000 