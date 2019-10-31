## Ruby on Rails: Blog with Comment functionality

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
   
* Database creation
    - ``rails g model Post title:string content:text``
    - ``rake routes`` check routes
    - ``rails console`` -> ``@post = Post`` -> ``@post.connection`` -> ``@post.all`` -> ``@post = Post.find(8)`` -> ``@post`` -> ``@post.title = "this is a post updated from rails console"`` -> ``@post.save`` (updating database from CLI)

* Database initialization
    - ``rails db:migrate``
    - ``rails g migration AddPostIdToComments``

* Deployment instructions: 
   - ``bundle``
   - ``rails s``
   
