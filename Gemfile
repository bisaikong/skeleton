source 'https://rubygems.org'

gem 'rails', '3.2.13'

gem 'jquery-rails'
gem 'bootstrap-sass'
gem 'simple_form'

#gem 'rails_admin'
#gem 'devise'

#gem 'capistrano'

group :test, :development do
  gem 'sqlite3'
  gem 'fabrication'
  gem 'faker'
  gem 'pry'
  gem 'rspec-rails'
end

group :development do
  gem 'letter_opener'
end

group :test do
  gem 'shoulda-matchers'
  gem 'capybara'
  #gem 'capybara-email'
  #gem 'selenium-webdriver'
  #gem 'database_cleaner'
end

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
end

group :production do
  gem 'pg'
  gem 'unicorn'
end