# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

# UP and Running

Copy environment variable files (change values if needed)

```
cp .env-sample .env
```

Build the required containers

```
docker-compose build
```

Create development and test databases

```
docker-compose run web bundle exec rails db:prepare
```

Run application with database
```
docker-compose up
```

Enjoy!
