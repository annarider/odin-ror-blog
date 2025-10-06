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
- (Follow Heroku's instructions)[https://devcenter.heroku.com/articles/getting-started-with-rails8]
- Remember to set the production database URL since Heroku uses an add-on 
extension for PostgreSQL
```
production:
  primary:
    <<: *default
    url: <%= ENV.fetch("DATABASE_URL") %>
```

* ...
