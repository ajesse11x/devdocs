source 'https://rubygems.org'
ruby '2.5.1'

gem 'rake', '>= 12.3.3'
gem 'thor'
gem 'pry', '~> 0.11.0'
gem 'activesupport', '~> 6.1', '>= 6.1.7.3', require: false
gem 'yajl-ruby', '>= 1.4.2', require: false

group :app do
  gem 'rack', '>= 3.0.0'
  gem 'sinatra', '>= 2.2.3'
  gem 'sinatra-contrib', '>= 2.2.3'
  gem 'rack-ssl-enforcer'
  gem 'thin'
  gem 'sprockets', '>= 4.2.0'
  gem 'sprockets-helpers'
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
  gem 'better_errors', '>= 2.8.0'
end

group :docs do
  gem 'typhoeus'
  gem 'nokogiri', '>= 1.13.9'
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
  gem 'rack-test', '>= 2.0.0', require: false
end

if ENV['SELENIUM'] == '1'
  gem 'capybara'
  gem 'selenium-webdriver'
end
