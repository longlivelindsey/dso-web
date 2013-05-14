source 'https://rubygems.org'

ruby '2.0.0'
gem 'rails', '3.2.13'
gem 'thin'

# Use MongoDB
gem 'mongoid'
gem 'bson_ext'
gem 'mongo_ext'

# JQuery served via CDN
gem 'jquery-rails'
gem 'jquery-rails-cdn'

# Force newer slim version
gem 'slim', '>= 1.3.8'
gem 'slim-rails'

# Let's have some admin interface
gem 'activeadmin-mongoid', git: "git://github.com/elia/activeadmin-mongoid.git"
gem 'activeadmin', '0.5.1' # Force version 0.5.1 for Mongoid compatibility
gem 'devise'

# How about some easy file attachments using AWS?
gem "mongoid-paperclip", :require => "mongoid_paperclip"
gem 'aws-sdk', '~> 1.3.4'

# Gems used only for assets
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'bootstrap-sass', '~> 2.3.1.0'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier',     '>= 1.0.3'
end

# Gems for testing and development
group :development, :test do
  gem 'rspec-rails'
  gem 'guard-rspec'
  gem 'debugger'
  gem 'capybara'
end
