FROM python:3.9-slim

WORKDIR /app

RUN pip install --no-cache-dir requests

COPY request_generator.py .

CMD ["python", "request_generator.py"]