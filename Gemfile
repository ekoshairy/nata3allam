source 'https://rubygems.org'

gem 'rails',                '3.2.12'
gem 'mongoid',              '~> 3.1.0'
gem 'devise',               '~> 2.2.3'
gem 'tire',                 '~> 0.5.5'
gem 'tire-contrib',         '~> 0.1.1'
gem 'haml-rails',           '0.3.4'
gem 'routing-filter',       '0.3.1'
gem 'carrierwave-mongoid',  github: 'carrierwaveuploader/carrierwave-mongoid', branch: 'master', require: 'carrierwave/mongoid'
gem 'mongoid_slug',         '2.0.1'
gem 'mini_magick',          '3.4'
gem "json_builder",         "~> 3.1.7"
gem 'dynamic_form',         '1.1.4'
gem 'kaminari',             '0.13.0'
gem "jquery-rails",         "2.3.0"


group :assets do
  gem 'hogan_assets'
  gem 'sass-rails',         '~> 3.2.3'
  gem 'bootstrap-sass',     '~> 2.3.1.2'
  gem 'coffee-rails',       '~> 3.2.1'
  gem 'compass-rails'
  gem 'modular-scale'
  gem 'sassy-math'
  gem 'morrisjs-rails'
  gem 'raphael-rails'
  gem 'best_in_place', '~> 2.1.0'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  gem 'therubyracer'        , '~> 0.11.0' , :platforms => :ruby
  gem 'libv8'               , '~> 3.11.8'

  gem 'uglifier', '>= 1.0.3'
  gem "roadie",   "~> 2.3.4"
end

group :development do
  gem 'debugger'
  gem 'awesome_print',     '1.0.2'
  gem 'mongrel',           '1.2.0.pre2'
  gem 'sextant'
  gem "letter_opener"
  gem 'binding_of_caller'
  gem "better_errors"
  gem 'meta_request'
  gem 'rack-webconsole'
  gem 'faker', '~> 1.0.1', :group => :development
  # Guard
  gem 'guard-bundler'
  gem 'guard-livereload'
  gem 'guard-rspec'
  gem 'guard-cucumber'
  gem 'zeus'
  gem 'rack-test', require: 'rack/test'
end

group :test do
  gem 'debugger'
  gem 'cucumber',            '1.2.5'
  gem 'cucumber-rails',      '1.3.1', require: false
  gem 'database_cleaner'
  gem 'factory_girl_rails',  '4.2.1'
  gem 'forgery',             '0.5.0'
  gem 'capybara',            '2.1.0.beta1'
  gem 'rspec-rails',         '2.12.2'
  gem 'selenium-webdriver'
  gem 'fuubar'
  gem 'fuubar-cucumber'
  gem 'email_spec'
end
