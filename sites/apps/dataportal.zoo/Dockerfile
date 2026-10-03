FROM python:3-alpine
WORKDIR /app
COPY app.py dataset.json ./
ENV PORT=8080 DATAPORTAL_DATA=/app/dataset.json
EXPOSE 8080
CMD ["python3", "app.py"]
