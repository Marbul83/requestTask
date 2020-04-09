FROM python:3.6
WORKDIR /app
COPY requirements.txt .
RUN pip3 install -r requirements.txt
EXPOSE 5001
ENTRYPOINT ["/usr/local/bin/python3", "app.py"]
COPY . .
