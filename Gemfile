source 'https://rubygems.org'

ruby '2.2.0'

# Gems required in all environments
gem 'rails', '7.0.0'

gem 'puma', '>= 2.12.0'
gem 'puma_auto_tune', github: 'schneems/puma_auto_tune'
gem 'sprockets_better_errors'
gem 'skylight'
gem 'git_hub_bub'
gem 'pg'
gem 'resque', '>= 2.2.1'
gem 'resque_def'
gem 'omniauth', github: 'schneems/omniauth', branch: 'schneems/hashie-breakup'
gem 'omniauth-github'
gem 'will_paginate'
gem 'httparty'
gem 'dalli'
gem 'wicked', '>= 1.2.1'
gem 'rails_autolink', '>= 1.1.8'
gem 'bluecloth'
gem 'maildown', '>= 2.0.1'
gem 'rrrretry'
gem 'jquery-rails'
gem 'devise'
gem 'rack-timeout'
gem 'unicorn', '>= 5.1.0'
gem 'mail_view', '~> 1.0.2'
gem 'valid_email'
gem 'sass-rails', '~> 6.0.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'uglifier', '>= 1.0.3'

group :development do
  gem 'foreman'
  gem 'quiet_assets'
  gem 'spring'
  gem 'web-console', '~> 3.0', '>= 3.0.0'
end

group :test do
  gem 'capybara', '2.3.0'
  # Not essential but helpful for save_and_open_page
  gem 'launchy'
  gem 'webmock'
  gem 'vcr'
  gem 'mocha', require: false
  gem 'simplecov', require: false
end

group :development, :test do
  gem 'teaspoon', '>= 0.7.9'
  gem 'dotenv-rails'
end

group :production do
  gem 'rails_12factor'
end
