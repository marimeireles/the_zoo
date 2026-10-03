FROM python:3-alpine
WORKDIR /app
COPY app.py dataset.json wiki_facts.json ./
ENV PORT=8080 QUIZ_DATA=/app/dataset.json QUIZ_WIKI_FACTS=/app/wiki_facts.json R1_WINDOW=60 DOWNTIME=20 RN_WINDOW=12 N_ROUNDS=5
EXPOSE 8080
CMD ["python3", "app.py"]
