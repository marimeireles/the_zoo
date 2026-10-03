# Legacy dev-wiki for the Zoo. Reproduces the DSEWiki GET-write quirk. Stdlib only, no network at build.
FROM python:3-alpine
WORKDIR /app
COPY app.py .
ENV PORT=8080 DEVWIKI_DATA=/data/pages.json
EXPOSE 8080
CMD ["python3", "app.py"]
