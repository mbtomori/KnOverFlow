source 'https://rubygems.org'

gem 'rails', '3.2.13'
gem 'bcrypt-ruby', '~> 3.0.0'
gem 'debugger'

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

group :development, :test do
  gem 'sqlite3'
  gem 'rspec-rails'
  gem 'faker'
  gem 'factory_girl_rails'
  gem 'shoulda-matchers'
  gem 'simplecov', :require => false
  gem 'capybara'
  gem 'turn', '< 0.8.3' # pretty printing for tests
  gem 'guard-rspec' # auto-run tests
  # gem 'ruby_gntp' # growl notify
  gem 'rb-fsevent' #notifies when files change
end

gem 'pry-rails', :group => :development

group :production do
  gem 'pg'
end
