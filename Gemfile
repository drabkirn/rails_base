source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.1'

gem 'rails', '~> 6.0.3.3'
gem 'mysql2', '~> 0.5.3'
gem 'puma', '~> 4.3'
gem 'webpacker', '~> 5.2'
gem 'jbuilder', '~> 2.9', '>= 2.9.1'
gem 'bootsnap', '~> 1.4', require: false
gem 'tzinfo-data', '~> 1.2020'

# Delete these if using React/other for FE - START
gem 'sass-rails', '>= 6'
gem 'turbolinks', '~> 5.2', '>= 5.2.1'
# Delete these if using React/other for FE - END

group :development, :test do
  gem 'byebug', '~> 11.1', platforms: [:mri, :mingw, :x64_mingw]

  # Custom gems:
  gem 'database_cleaner', '~> 1.8', '>= 1.8.5'
  gem 'simplecov', '~> 0.19.0'
  gem 'shoulda-matchers', '~> 4.4'
  gem 'rails-controller-testing', '~> 1.0'
  gem 'rspec-rails', '~> 4.0'
  gem 'factory_bot_rails', '~> 6.1'
  gem 'faker', '~> 2.16'
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '~> 4.0'
  gem 'listen', '~> 3.2', '>= 3.2.1'
  gem 'spring', '~> 2.1'
  gem 'spring-watcher-listen', '~> 2.0', '>= 2.0.1'

  # Custom gems:
  gem 'brakeman', '~> 4.9'
  gem 'bundler-audit', '~> 0.7.0'
end

group :test do
  gem 'capybara', '~> 3.33'
  gem 'selenium-webdriver', '~> 3.142', '>= 3.142.6'
  gem 'webdrivers', '~> 4.4'
end

## Custom Gems:
gem 'figaro', '~> 1.1', '>= 1.1.1'