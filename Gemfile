source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.1'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.0.3', '>= 6.0.3.5'
# Gem to mongodb
gem 'mongoid', '~> 7.0.5'
# Use Puma as the app server
gem 'puma', '~> 4.1'
# Use SCSS for stylesheets
gem 'sass-rails', '>= 6'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '~> 4.0'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.7'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
gem 'bcrypt', '~> 3.1.7'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.2', require: false

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'rspec-rails'
  gem 'factory_bot_rails'
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

group :test do
  gem 'database_cleaner', '1.8.5'
  gem 'faker'
  gem 'capybara'
  gem 'mongoid-rspec'
  gem 'rails-controller-testing'
  gem 'selenium-webdriver'
  gem 'rspec-sidekiq'
end

# Template engine
gem 'hamlit-rails'

# Authorization
gem 'omniauth-twitter', :github => 'arunagw/omniauth-twitter'
# gem 'omniauth-instagram-graph'
gem 'omniauth-facebook', '~> 8.0.0'
gem 'omniauth-rails_csrf_protection'

# Twitter API
gem 'twitter'
# Facebook API
gem 'koala'

gem 'simple_form'

gem 'carrierwave', '~> 2.2.1'
gem 'carrierwave-mongoid', :require => 'carrierwave/mongoid'

# Sidekiq
gem 'sidekiq'

# Kaminari
gem 'kaminari-mongoid'
gem 'kaminari-actionview'
