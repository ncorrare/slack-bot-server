source 'http://rubygems.org'

ruby '2.1.8'

gem 'slack-ruby-bot', '~> 0.7.0'
gem 'mongoid', '~> 5.0.0'
gem 'unicorn'
gem 'grape', '~> 0.14.0'
gem 'grape-roar'
gem 'rack-cors'
gem 'kaminari', '~> 0.16.1', require: 'kaminari/grape'
gem 'grape-swagger'
gem 'mongoid-scroll'
gem 'rack-robotz'
gem 'newrelic_rpm'
gem 'newrelic-slack-ruby-bot'
gem 'rack-rewrite'
gem 'rack-server-pages'
gem 'gctools', require: 'gctools/oobgc'

group :development, :test do
  gem 'rake', '~> 10.4'
  gem 'rubocop', '0.35.1'
  gem 'foreman'
end

group :development do
  gem 'mongoid-shell'
  gem 'heroku'
end

group :test do
  gem 'rspec'
  gem 'rack-test'
  gem 'webmock'
  gem 'vcr'
  gem 'fabrication'
  gem 'faker'
  gem 'database_cleaner'
  gem 'hyperclient'
  gem 'capybara'
  gem 'selenium-webdriver'
end
