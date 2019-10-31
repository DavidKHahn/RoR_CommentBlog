# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version: 2.6.5

* System dependencies:

    **Guard is a command line tool to easily handle events on file system modifications.**
    
    gem 'guard', '~> 2.15', '>= 2.15.1'
    
    **Guard::LiveReload automatically reloads your browser when 'view' files are modified.**
    
    gem 'guard-livereload', '~> 2.5', '>= 2.5.2', require: false

* Configuration
    - ``rails s``
    - ``bundle``
    - ``rails generate simple_form:install``
    - ``guard init livereload`` Useful for reloading of browser automatically when changes are made
    - ``bundle exec guard``
    - ``rails g controller posts`` Creation of posts
    - ``rails g model Post title:string content:text``
    - ``rails db:migrate``
    
* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
