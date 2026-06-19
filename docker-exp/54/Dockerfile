FROM python:3.12-slim

WORKDIR /app

COPY index.html .

EXPOSE 5000

CMD ["python", "-m", "http.server", "5000"]