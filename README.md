# Django & React application

This is a set up so that we can easily create apps that use Django on the backend (and take advantage of the amazing admin UI) and React (set up with [`create-react-app`](https://npm.im/create-react-app)) for the front end application.

## Running

1. `docker-compose build`
1. `docker-compose up`
1. There should now be two servers running:
  - [http://127.0.0.1:8000](http://127.0.0.1:5000) is the Django app
  - [http://127.0.0.1:3000](http://127.0.0.1:3000) is the React app

## Using `docker-compose run` to issue one-off commands

If you want to run a one-off command, like installing dependencies, you can use the `docker-compose run <service_name> <cmd>`.
