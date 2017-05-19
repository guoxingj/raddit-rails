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

Note/bug need to be handled: 

every time after running bundle install, run

gem uninstall bcrypt-ruby
gem uninstall bcrypt
gem install bcrypt --platform=ruby
bundle install 

