FROM python:3.11-slim
WORKDIR /app
COPY . /app
RUN apt-get update -y && apt-get install -y libpq-dev gcc
RUN pip install -r requirements.txt
EXPOSE 5153
CMD ["python", "app.py"]