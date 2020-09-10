# Onboarding-chatbot
Implementation of a chatbot for the winter school course of the UI Design with RASA.

## Intents

- Greets
- Class information
- Information of a specific class
- Gratefulness

## Install Rasa

$ sudo apt update

$ sudo apt install python3-dev python3-pip

Create and activate a virtual environment:

$ python3 -m venv ./venv

$ source ./venv/bin/activate


Install Rasa

$ pip install -U pip

$ pip install rasa

## Train 

$ rasa train

## Run

$ rasa run actions & rasa shell
