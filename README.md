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

* ...

# Commands

```
bin/rails generate controller Articles index --skip-routes

bin/rails generate model Article title:string body:text
bin/rails db:migrate

bin/rails generate model Comment commenter:string body:text article:references
bin/rails db:migrate

bin/rails generate controller Comments

bin/rails generate migration AddStatusToArticles status:string
bin/rails generate migration AddStatusToComments status:string
bin/rails db:migrate
```
