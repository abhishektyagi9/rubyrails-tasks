source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.1.6'
# Use twitter-bootstrap-rails
gem 'therubyracer'
gem 'less-rails'
gem 'twitter-bootstrap-rails'
gem 'jquery-rails'
# Use postgresql as the database for Active Record
gem 'pg', '>= 0.18', '< 2.0'
# Use Puma as the app server
gem 'puma', '~> 3.7'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

#customer gems

gem 'aasm', '~> 5.0.8'
gem 'active_storage_validations', '~> 0.8.9'
gem 'administrate', '>= 0.12'
gem 'administrate-field-active_storage'
gem 'administrate-field-nested_has_many'
gem 'administrate-field-scoped_has_many'
gem 'aws-sdk-s3', require: false
gem 'azure-storage', '~> 0.14.0.preview'
gem 'bootstrap4-kaminari-views' # for adminstrate's pagination
gem 'devise', '~> 4.7.3'
gem 'faker'
gem 'money-rails', '~> 1'
gem 'newrelic_rpm'
gem 'phony_rails', '~> 0.14.13'

gem 'pundit'
gem 'rails-settings-cached', '~> 2.0'
gem 'sidekiq'
gem 'sprockets', '3.7.2'
gem 'twilio-ruby', '~> 5.45.0'

# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
