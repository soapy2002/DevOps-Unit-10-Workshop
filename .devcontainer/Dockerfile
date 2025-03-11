FROM python:3.11

# Install the Azure CLI
RUN curl -sL https://aka.ms/InstallAzureCLIDeb | bash

COPY . /workshop_exercise

WORKDIR /workshop_exercise

RUN pip install -r requirements.txt