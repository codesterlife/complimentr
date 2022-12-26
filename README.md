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

### Disclaimer

This Project was did as a part of the [APIs for Beginners](https://www.freecodecamp.org/news/apis-for-beginners-full-course/) course on [FreeCodeCamp](https://www.freecodecamp.org/) by [Craig Dennis](https://github.com/craigsdennis). This project was supposed to be deployed using Glitch as per the course instruction. But I had to try it out using a different method I learned. I hope I don't get in trouble for this. :grimacing: :sweat_smile:

### Deployment

This Project has been deployed in [Render](https://render.com/) cloud service. 

#### [Click Here](https://complimentr.onrender.com)
