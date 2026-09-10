# Dockerfile del FRONT — Flask + Jinja2 + Bootstrap (puerto 8062)
FROM python:3.12-slim
WORKDIR /app
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt
COPY . .
ENV PUERTO=8062
EXPOSE 8062
CMD ["python", "app.py"]
