FROM python:3-alpine
LABEL version="1.0.0"
COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt
CMD python /app/app.py
