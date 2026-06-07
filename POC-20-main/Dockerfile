FROM python:3.11-slim

WORKDIR /app

COPY . .

# Install dependencies if requirements.txt exists
RUN pip install --no-cache-dir -r requirements.txt || true

EXPOSE 8080

CMD ["python", "main.py"]
