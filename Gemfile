source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.2"

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem "rails", "~> 7.0.4"

# The original asset pipeline for Rails [https://github.com/rails/sprockets-rails]
gem "sprockets-rails"

# Use sqlite3 as the database for Active Record
gem "sqlite3", "~> 1.4"

# Use the Puma web server [https://github.com/puma/puma]
gem "puma", "~> 5.0"

# Use JavaScript with ESM import maps [https://github.com/rails/importmap-rails]
gem "importmap-rails"

#SCSS File
gem 'sass-rails', '~> 6.0'

#uglifier
gem 'uglifier', '~> 4.2'

#turbo links
gem 'turbolinks', '~> 5.2', '>= 5.2.1'

# Hotwire's SPA-like page accelerator [https://turbo.hotwired.dev]
gem "turbo-rails"

#devise
gem 'devise', '~> 4.8', '>= 4.8.1'

#gravatar_image_tag
gem 'gravatar_image_tag', '~> 1.2'

#jquery-rails
gem 'jquery-rails', '~> 4.5'

#rolify
gem 'rolify', '~> 6.0'

# cancancan
gem 'cancancan', '~> 3.4'

#friendly_id
gem 'friendly_id', '~> 5.4', '>= 5.4.2'

#redcarpet
gem 'redcarpet', '~> 3.5', '>= 3.5.1'

#coderay
gem 'coderay', '~> 1.1', '>= 1.1.3'


#coffee-rails
gem 'coffee-rails', '~> 5.0'

# Hotwire's modest JavaScript framework [https://stimulus.hotwired.dev]
gem "stimulus-rails"

# Build JSON APIs with ease [https://github.com/rails/jbuilder]
gem "jbuilder"

#Bulma CSS
gem 'bulma-rails', '~> 0.9.4'
#Bootstrap
gem 'bootstrap', '~> 5.2', '>= 5.2.2'
#Simple_Form
gem 'simple_form', '~> 5.1'

# Use Redis adapter to run Action Cable in production
# gem "redis", "~> 4.0"

# Use Kredis to get higher-level data types in Redis [https://github.com/rails/kredis]
# gem "kredis"

# Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
# gem "bcrypt", "~> 3.1.7"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", require: false

# Use Sass to process CSS
# gem "sassc-rails"

# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem "image_processing", "~> 1.2"

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
  gem 'byebug', '~> 11.1', '>= 11.1.3'
end

group :development do
  # Use console on exceptions pages [https://github.com/rails/web-console]
  gem 'listen', '~> 3.7', '>= 3.7.1'
  #spring
  gem 'spring', '~> 4.1'
  gem 'spring-watcher-listen', '~> 2.1'
  gem "web-console"

  #Guard
gem 'guard', '~> 2.18'
gem 'guard-livereload', '~> 2.5', '>= 2.5.2' , require: false


#Make Error Better Looking
gem 'better_errors', '~> 2.9', '>= 2.9.1'

  # Add speed badges [https://github.com/MiniProfiler/rack-mini-profiler]
  # gem "rack-mini-profiler"

  # Speed up commands on slow machines / big apps [https://github.com/rails/spring]
  # gem "spring"
end

group :test do
  # Use system testing [https://guides.rubyonrails.org/testing.html#system-testing]
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end
