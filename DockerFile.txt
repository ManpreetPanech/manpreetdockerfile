# Dockerfile
FROM python:3.10-slim
COPY manpreet.py /manpreet.py
CMD ["python", "/manpreet.py"]
