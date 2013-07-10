source "https://rubygems.org"

gem "rails", git: "git://github.com/rails/rails.git", branch: "3-2-stable"

gem "exception_notification"

gem "capistrano"
gem "open4"
gem "syntax"
gem "version_fu", :github => "jmckible/version_fu"
gem "devise"
gem "devise-encryptable"
gem "pg"

group :development do
  gem "thin"

  gem "debugger"
  gem "pry"
  gem "pry-rails"
end

group :test do
  gem "mocha", :require => false
  gem "factory_girl_rails"
  gem "database_cleaner"
  gem 'minitest-reporters'
end

group :production do
  gem "unicorn"
end

group :assets do
  gem "jquery-rails"
  gem "uglifier"
  gem 'therubyracer'
end

if File.exists?('config/Gemfile.extras')
  eval File.read('config/Gemfile.extras')
end
