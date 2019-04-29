source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.3'

# System
gem 'pg'
gem 'puma', '~> 3.11'
gem 'rails', '~> 5.2.2'

gem 'sidekiq'
# Trailblazer bundle
gem 'dry-validation', '0.11.1'
gem 'trailblazer-endpoint', github: 'trailblazer/trailblazer-endpoint'
gem 'trailblazer-rails'

# Pagination
gem 'pagy'

# JSON::API Serializer
gem 'jsonapi-rails', github: 'jsonapi-rb/jsonapi-rails'

# Authentication
gem 'bcrypt'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false

group :development, :test do
  gem 'bullet'
  gem 'factory_bot_rails'
  gem 'ffaker'
  gem 'pry-byebug'
  gem 'pry-rails'
  gem 'rspec-rails'
  gem 'shoulda-matchers', github: 'thoughtbot/shoulda-matchers'

  gem 'rubocop', require: false
  gem 'rubocop-rspec', require: false
  gem 'simplecov'
  gem 'simplecov-lcov'
end

group :development do
  gem 'letter_opener'
  gem 'letter_opener_web', github: 'fgrehm/letter_opener_web', ref: 'd6c6455' # branch with fixed sprockets dependency
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  gem 'dox', require: false
  gem 'json_matchers'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
