source 'https://ruby.taobao.org/'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 4.2.7.1'
# Use mysql as the database for Active Record
gem 'mysql2', '>= 0.3.13', '< 0.5'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks', github: 'turbolinks/turbolinks-classic'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platform: :mri
  gem 'pry-byebug', platform: :mri
  gem 'pry-rails', platform: :mri
  gem 'better_errors', platform: :mri

  gem 'dotenv-rails', :require => 'dotenv/rails-now'

  gem 'capistrano', '~> 3.5'
  gem 'capistrano-rails', '~> 1.1'
  gem 'capistrano-rvm'
  gem 'capistrano-sidekiq', github: 'seuros/capistrano-sidekiq'
  gem 'capistrano3-unicorn'
end

group :development, :staging, :test do
  gem 'faker'
  # gem 'oneapm_rpm'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'
end

gem 'slim-rails'
gem 'kaminari'
gem 'rails-i18n', '~> 4.0.0'

gem 'semantic-ui-sass', github: 'doabit/semantic-ui-sass'

# gem 'sneakers'
gem 'ruby-ole'
gem 'spreadsheet'

gem 'cancancan', '~> 1.10'

gem 'rack-cors'

gem 'sidekiq', '~> 4.0.0'
gem 'sinatra', :require => nil

gem 'redis', '~> 3.0'

gem 'exception_notification'

# ip db
gem 'maxminddb'
gem 'geocoder'
# geo class
# gem 'geo_coord', require: 'geo/coord'

# notification
gem 'apnotic'
gem 'gcm'

# call limit
gem 'rack-attack'
gem 'redis-rails'

gem 'whenever', require: false
gem 'nokogiri', '>= 1.6.8'
