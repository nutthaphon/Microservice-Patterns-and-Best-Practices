FROM python:3.6.1 

COPY pip.conf /root/.config/pip/pip.conf

COPY . /app 
 
WORKDIR /app 

RUN pip install --upgrade pip

RUN pip install -r requirements.txt 
 
ENTRYPOINT ["python"] 
 
CMD ["app.py"] 
 
EXPOSE 5000 