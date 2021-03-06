source 'https://rubygems.org'

####### ADDED GEMS ################################
gem 'figaro'
gem 'httparty'
gem 'awesome_print', require: 'ap'
gem 'tinymce-rails'
gem 'pg'
gem 'font-awesome-rails'
gem 'materialize-sass'
gem 'angularjs-file-upload-rails', '~> 2.2.0'
gem 'octokit'

#angular
gem 'angularjs-rails'
gem 'angular_rails_csrf'

#dependencies from bower
source "https://rails-assets.org" do
  gem 'rails-assets-angular-devise'
  gem 'rails-assets-angular-animate'
  gem 'rails-assets-angular-dragdrop'
  gem 'rails-assets-angular-utf8-base64'
  gem 'rails-assets-bootstrap-material-design'
  gem 'rails-assets-angular-flash-alert'
  gem 'rails-assets-pluralize'
end

#devise
gem 'devise'
gem 'omniauth-github'

#uploads
gem 'paperclip'
gem 'aws-sdk', '~> 2.3'


group :development do
  gem 'hirb'
  gem 'guard-rspec', require: false
  gem "better_errors"
  gem 'binding_of_caller'
end

group :development, :test do
  gem 'pry-byebug'
  gem 'rspec-rails'
  gem 'factory_girl_rails', '~> 4.0'
  gem 'shoulda-matchers'
  gem 'capybara'
  gem 'launchy'
  gem 'faker'

  # test stuff
  gem 'jasmine'
end

#########################################################################

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.0.0', '>= 5.0.0.1'
# Use sqlite3 as the database for Active Record
# Use Puma as the app server
gem 'puma', '~> 3.0'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console'
  gem 'listen', '~> 3.0.5'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
