source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.5'
# Use sqlite3 as the database for Active Record
gem 'pg'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development do
#   gem 'rails_email_preview'
  gem 'letter_opener'                       # => open emails in a new browser-window
  gem "better_errors"                       # => much better and more useful error page
  # gem "binding_of_caller"                   # => makes better_errors even better (variables ...)
  gem 'bullet'                              # => alert bad db-queries
  gem 'quiet_assets'                        # => shortened log from asset-pipeline
  # gem "thin"

  # gem 'capistrano', '~> 3.2.0'
  # gem 'capistrano-rails', '~> 1.1'
#   gem 'capistrano-bundler', '~> 1.1.2'
#   gem 'rvm1-capistrano3', require: false
#   gem 'capistrano-sidekiq'
  gem 'pry-byebug'
  gem 'pry-stack_explorer'
  gem 'awesome_print'
#   gem 'hipchat'
end

group :development, :test do
#   gem 'jasmine-rails'
  gem "rspec"#,                "~> 3.0.0"
  gem 'rspec-rails'#,          '~> 3.0.0'
end

# group :assets do
#   gem 'therubyracer', :platforms => :ruby
# end

group :test do
  gem 'rspec-html-matchers'
  gem 'shoulda-matchers'

  gem 'rspec-legacy_formatters'
  gem 'rspec_junit_formatter'

  gem 'fuubar'
  # gem 'parallel_tests'
  gem 'rspec-rerun'
  gem 'simplecov'
  # gem 'simplecov-bamboo', :require => false, :group => "test"

  gem 'database_cleaner',     '~> 1.2.0'

  gem 'timecop'
  gem 'test_after_commit'
  gem 'poltergeist', git: 'https://github.com/teampoltergeist/poltergeist.git', ref: '2d23867279e1ccd7e064a51bb750ea75a71ecd0e'
  gem "capybara"
  gem 'capybara-screenshot'
  gem 'selenium-webdriver'
  gem "site_prism"

#   gem 'guard'
#   gem 'guard-zeus'
#   gem 'guard-rspec'
#   gem 'guard-bundler'
#   gem 'guard-migrate'
end
