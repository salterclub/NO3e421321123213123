# Accord - API

Tested code that brings Accord to life.

![Lines of Code](https://img.shields.io/tokei/lines/github/d-clone/API?color=46828d&style=for-the-badge)

> © All rights reserved. This repo is not (yet) open source, and is awaiting completion.

## Non-Docker Setup .env

If you are not using Docker, you can use the following template as a guide.

### `.env`

```.env
API_URL="http://localhost:3000/api"
EMAIL_ADDRESS="example@gmail.com"
EMAIL_PASSWORD="google_account_password"
MONGO_URI="mongodb://localhost/accord"
PORT=3000
ROOT_ENDPOINT="http://localhost:3000"
WEBSITE_URL="http://localhost:4200"
```

## Docker Setup .env

If you are using Docker, some variables will be substituted by Docker.

```.env
API_URL="http://localhost:3000/api"
EMAIL_ADDRESS="example@gmail.com"
EMAIL_PASSWORD="google_account_password"
MONGO_URI="mongodb://database/accord"
PORT=3000
ROOT_ENDPOINT="http://localhost:3000"
WEBSITE_URL="http://localhost:4200"
```

> For help on setting up gmail, go here - https://nodemailer.com/usage/using-gmail.
