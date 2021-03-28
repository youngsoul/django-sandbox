# pull base image
FROM python:3.8

# Set environment variables
ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

# set working directory in container
WORKDIR /code

# Install Dependencies
COPY requirements.txt /code/
RUN pip install -r requirements.txt

# Copy project code from local into container
COPY . /code/
