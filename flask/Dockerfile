FROM registry.access.redhat.com/ubi8/python-38
WORKDIR ./app 
COPY requirements.txt .
RUN pip install -r requirements.txt --no-cache-dir
COPY . .
ENTRYPOINT ["python"] 
CMD ["app.py"]
