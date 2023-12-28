# Use an official Python runtime as a parent image
FROM python:3.10

# Set environment varibles
ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

# Set work directory
WORKDIR /

COPY src/templates/*.html ./

RUN ls

CMD ["python", "-m", "http.server", "8081"]
