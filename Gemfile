source 'https://rubygems.org'
ruby '2.5.1'

gem 'rake'
gem 'thor'
gem 'pry', '~> 0.11.0'
gem 'activesupport', '~> 5.2', require: false
gem 'yajl-ruby', require: false

group :app do
  gem 'rack', '>= 2.1.3'
  gem 'sinatra', '>= 2.0.4'
  gem 'sinatra-contrib', '>= 2.0.4'
  gem 'rack-ssl-enforcer'
  gem 'thin', '>= 1.7.2'
  gem 'sprockets', '>= 3.7.2'
  gem 'sprockets-helpers', '>= 1.2.1'
  gem 'erubi'
  gem 'browser'
  gem 'sass'
  gem 'coffee-script'
end

group :production do
  gem 'uglifier'
  gem 'newrelic_rpm'
end

group :development do
  gem 'better_errors', '>= 2.5.0'
end

group :docs do
  gem 'typhoeus'
  gem 'nokogiri'
  gem 'html-pipeline'
  gem 'image_optim'
  gem 'image_optim_pack', platforms: :ruby
  gem 'progress_bar', require: false
  gem 'unix_utils', require: false
  gem 'tty-pager', require: false
end

group :test do
  gem 'minitest'
  gem 'rr', require: false
  gem 'rack-test', '>= 1.1.0', require: false
end

if ENV['SELENIUM'] == '1'
  gem 'capybara'
  gem 'selenium-webdriver'
end
