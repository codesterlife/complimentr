# Complimentr

This application is meant to be used with the [Introduction to APIs course](https://github.com/craigsdennis/intro-to-apis-course).

## Local Installation

Copy `.env.example` to `.env` and update it with your [Twilio](https://twilio.com) credentials.

### Running the application

* `pip install pipenv`
* `pipenv shell`
* `pip install -r requirements.txt`
* `FLASK_ENV=development flask run`

#### In Development mode

* `gunicorn app:app`
