source "https://rubygems.org"

gem "rails", "3.2.8"

gem "exception_notification"

gem "capistrano"
gem "open4"
gem "syntax"
gem "version_fu", :github => "jmckible/version_fu"
gem 'devise'
gem 'devise-encryptable'

group :development do
  gem "sqlite3"
  gem "thin"

  gem 'debugger'
  gem "pry"
  gem "pry-rails"
end

group :test do
  gem "sqlite3"

  gem "mocha"
  gem 'spork'
end

group :production do
  gem "mysql2"
  gem "unicorn"
end

group :assets do
  gem "sass-rails"
  gem "compass"
  gem "compass-rails"

  gem "jquery-rails"
end
