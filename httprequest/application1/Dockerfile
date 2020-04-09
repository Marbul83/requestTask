FROM python:3.6
WORKDIR /app
COPY requirements.txt .
RUN pip3 install -r requirements.txt
EXPOSE 5000
ENTRYPOINT ["/usr/local/bin/python", "app.py"]
COPY . .


