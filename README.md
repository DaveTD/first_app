# Ruby on Rails Tutorial: first application

This is the first application for the
[*Ruby on Rails Tutorial*](http://railstutorial.org/)
by [Michael Hartl](http://michaelhartl.com/).


Gemfile has been modified from the book source to include execjs and therubyracer

On Fedora, heroku toolbelt will not work.  Use the following as a workaround:
 $ git clone https://github.com/heroku/heroku
 $ bundle install
 $ bundle exec rake tgz:build
