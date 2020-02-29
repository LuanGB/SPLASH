source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.3'

gem 'rails', '~> 5.2.3'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 3.12'

gem 'bootsnap', '>= 1.1.0', require: false

gem 'devise', '~> 4.6', '>= 4.6.2'
gem 'trailblazer-rails', '~> 2.1', '>= 2.1.7'
gem 'spotify-ruby', '~> 0.2.4'

group :development, :test do
  gem 'trailblazer-developer', '~> 0.0.3'
  gem 'dotenv', '~> 2.7', '>= 2.7.4'
  gem 'pry', '~> 0.12.2'
end

group :development do
  gem 'trailblazer-generator', '~> 0.2.0'
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  gem 'chromedriver-helper'
end
