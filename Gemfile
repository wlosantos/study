source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.0'

gem 'bootsnap', require: false
gem 'cssbundling-rails'
gem 'jsbundling-rails'
gem 'puma', '~> 5.0'
gem 'rails', '~> 7.0.2', '>= 7.0.2.3'
gem 'redis', '~> 4.0'
gem 'sprockets-rails'
gem 'sqlite3', '~> 1.4'
gem 'stimulus-rails'
gem 'turbo-rails'

gem 'enumerate_it'
gem 'simple_form'
gem 'slim'
gem 'slim-rails'

group :development, :test do
  gem 'awesome_print'
  gem 'better_errors', '>= 2.7.1'
  gem 'capybara', '~> 3.36'
  gem 'debug', platforms: %i[mri mingw x64_mingw]
  gem 'dotenv-rails'
  gem 'factory_bot_rails', '~> 6.1'
  gem 'faker'
  gem 'pry'
  gem 'pry-nav'
  gem 'pry-rails'
  gem 'rspec-rails'
  gem 'rubycritic', require: false
  gem 'selenium-webdriver'
  gem 'webdrivers'
end
group :development do
  gem 'rubocop'
  gem 'rubocop-fnando'
  gem 'rubocop-performance'
  gem 'rubocop-rails'
  gem 'web-console'
end

group :test do
  gem 'capybara-screenshot'
  gem 'database_cleaner', '~> 2.0', '>= 2.0.1'
  gem 'shoulda-matchers', '~> 4.5', '>= 4.5.1'
  gem 'simplecov', '~> 0.21.2', require: false
end
