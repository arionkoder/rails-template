source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.1'

gem 'bcrypt', '~> 3.1.7'
gem 'bootsnap', require: false
gem 'importmap-rails'
gem 'jbuilder'
gem 'kaminari', '~> 1.2.2'
gem 'pg'
gem 'pg_query', '~> 2.1', '>= 2.1.3'
gem 'pg_search', '~> 2.3', '>= 2.3.5'
gem 'puma', '~> 5.6'
gem 'pundit', '~> 2.2'
gem 'rails', '~> 7.0.1'
gem 'redis', '~> 4.0'
gem 'rubocop'
gem 'sassc-rails'
gem 'sidekiq', '~> 6.4', '>= 6.4.1'
gem 'sprockets-rails'
gem 'stimulus-rails'
gem 'turbo-rails'
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

group :development, :test do
  gem 'debug', platforms: %i[mri mingw x64_mingw]
  gem 'dotenv-rails', '~> 2.1', '>= 2.1.1'
  gem 'factory_bot_rails', '~> 6.2'
  gem 'faker', '~> 2.19'
  gem 'prosopite', '~> 1.0', '>= 1.0.7'
  gem 'pry-rails', '~> 0.3.9'
  gem 'rspec-rails', '~> 5.0.0'
end

group :development do
  gem 'better_errors', '~> 2.9', '>= 2.9.1'
  gem 'binding_of_caller'
  gem 'rails_best_practices'
  gem 'rubycritic', '~> 4.6', '>= 4.6.1', require: false
  gem 'web-console'
end

group :test do
  gem 'shoulda-matchers', '~> 5.0'
  gem 'simplecov', '~> 0.21.2', require: false
end
