source 'https://rubygems.org'

ruby '2.2.0'

# Gems required in all environments
gem 'rails', '7.1.0'

gem 'puma'
gem 'puma_auto_tune', github: 'schneems/puma_auto_tune'
gem 'sprockets_better_errors', '>= 0.0.5'
gem 'skylight'
gem 'git_hub_bub', '>= 1.0.0'
gem 'pg'
gem 'resque', '>= 1.25.0'
gem 'resque_def'
gem 'omniauth', github: 'schneems/omniauth', branch: 'schneems/hashie-breakup'
gem 'omniauth-github', '>= 2.0.0'
gem 'will_paginate'
gem 'httparty'
gem 'dalli'
gem 'wicked', '>= 1.2.1'
gem 'rails_autolink', '>= 1.1.8'
gem 'bluecloth'
gem 'maildown', '>= 2.0.1'
gem 'rrrretry'
gem 'jquery-rails', '>= 4.0.1'
gem 'devise', '>= 4.7.0'
gem 'rack-timeout'
gem 'unicorn'
gem 'mail_view', '~> 1.0.2'
gem 'valid_email', '>= 0.0.11'
gem 'sass-rails', '~> 6.0.0'
gem 'coffee-rails', '~> 4.2.2'
gem 'uglifier', '>= 1.0.3'

group :development do
  gem 'foreman'
  gem 'quiet_assets', '>= 1.0.3'
  gem 'spring'
  gem 'web-console', '~> 3.0', '>= 3.0.0'
end

group :test do
  gem 'capybara', '2.4.0'
  # Not essential but helpful for save_and_open_page
  gem 'launchy'
  gem 'webmock'
  gem 'vcr'
  gem 'mocha', require: false
  gem 'simplecov', require: false
end

group :development, :test do
  gem 'teaspoon', '>= 1.2.0'
  gem 'dotenv-rails'
end

group :production do
  gem 'rails_12factor'
end
