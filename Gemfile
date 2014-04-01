source 'https://rubygems.org'
ruby '2.1.1'
#ruby-gemset=railstutorial_rails_4_0

gem 'rails', '4.0.4'

group :development do
  gem 'sqlite3', '1.3.8'
end

gem 'sass-rails', '4.0.1'
gem 'uglifier', '2.1.1'
gem 'coffee-rails', '4.0.1'
gem 'jquery-rails', '3.0.4'
gem 'turbolinks', '1.1.1'
gem 'jbuilder', '1.0.2'

group :doc do
  gem 'sdoc', '0.3.20', require: false
end

group :production do
  gem 'pg', '0.15.1'
  gem 'rails_12factor', '0.0.2'
end

#I've always needed to add this and never understood how people can 
#write so many tutorials and completely miss it, or not need it
#I also know that I should have a "if ruby" around this, because
#JRuby or other ruby implementations will require different gems

#The tutorials are clearly using node. I have little to no interest
#in node.
gem 'execjs'
gem 'therubyracer'
