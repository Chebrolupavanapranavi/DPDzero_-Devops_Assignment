FROM python:3.9-slim

# Install curl
RUN apt-get update && apt-get install -y curl

WORKDIR /app
COPY . .
RUN pip install -r requirements.txt
CMD ["python", "app.py"]
