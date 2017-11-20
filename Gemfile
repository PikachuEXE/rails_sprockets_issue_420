source 'https://rubygems.org'

### Ruby Version
ruby '~> 2.3.0'


### Bundler Version
gem 'bundler'

### Rails
gem 'rails', '4.2.7.1'


# Use sqlite3 as the database for Active Record
gem 'sqlite3'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

gem 'sprockets-rails', require: 'sprockets/railtie'
# Limit the version to be 3.x until we are able to upgrade to 4.x
gem 'sprockets', '>= 4.0.0.beta4'

# Generates sprites and so so so much more that we have no idea about
gem 'compass-rails'
gem 'compass', '>= 0.12.7'
# Try to speed up SASS
# `1.0.5` is buggy, although it's required by the gem `compass`, we do not activate it
# gem 'compass-import-once', require: "compass/import-once/activate"

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Faster than Select2 with large local data set
gem 'chosen-rails'

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end

