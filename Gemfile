source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.1"

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem "rails", "~> 7.0.2.3"

# The original asset pipeline for Rails [https://github.com/rails/sprockets-rails]
gem "sprockets-rails"

# Use sqlite3 as the database for Active Record
gem "sqlite3", "~> 1.4"

# Use the Puma web server [https://github.com/puma/puma]
gem "puma", "~> 5.0"

# Bundle and transpile JavaScript [https://github.com/rails/jsbundling-rails]
gem "jsbundling-rails"

# Hotwire's SPA-like page accelerator [https://turbo.hotwired.dev]
gem "turbo-rails"

# Hotwire's modest JavaScript framework [https://stimulus.hotwired.dev]
gem "stimulus-rails"

# Bundle and process CSS [https://github.com/rails/cssbundling-rails]
gem "cssbundling-rails"

# Build JSON APIs with ease [https://github.com/rails/jbuilder]
gem "jbuilder"

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
gem "sassc-rails"

# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
gem "image_processing", "~> 1.2"

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
end

group :development do
  # Use console on exceptions pages [https://github.com/rails/web-console]
  gem "web-console"

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


# Chim's libraries
gem "paper_trail", git: "https://github.com/paper-trail-gem/paper_trail"
gem 'rails_admin', ['>= 3.0.0.beta2', '< 4']
gem 'devise'
gem "haml-rails", "~> 2.0"
gem 'simple_form'
gem 'country_select'
gem 'groupdate'
gem 'cancancan'
gem 'rails_admin_history_rollback'
gem 'friendly_id', '~> 5.4.0'
gem 'kaminari'
gem 'bootstrap5-kaminari-views'
gem 'ahoy_matey'
gem 'money-rails', '~>1.12'
gem "letter_opener", group: :development #amazing
gem 'discard', '~> 1.2'
gem 'rolify'
gem 'inline_svg'
gem "chartkick"

#Omniauth stuff
gem 'omniauth-google-oauth2'
gem 'omniauth-facebook'
gem 'omniauth-microsoft_graph'
gem 'omniauth-linkedin-oauth2'
gem 'omniauth-twitter'
gem 'omniauth-github', github: 'omniauth/omniauth-github', branch: 'master'
gem 'omniauth-quickbooks-oauth2', github: 'designium/omniauth-quickbooks-oauth2'
gem "omniauth-rails_csrf_protection"

gem "sassc-rails"

# Testing coverage etc

gem 'codecov', require: false, group: :test
gem 'simplecov', require: false, group: :test
