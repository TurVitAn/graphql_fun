source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.0'

gem 'bootsnap', '>= 1.4.4', require: false
gem 'graphql', '~> 1.12', '>= 1.12.14'
gem 'puma', '~> 5.0'
gem 'rails', '~> 6.1.4'
gem 'sqlite3', '~> 1.4'

group :development, :test do
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'rubocop-performance', '~> 1.11', '>= 1.11.3', require: false
  gem 'rubocop-rails', '~> 2.9', '>= 2.9.1', require: false
  gem 'rubocop-rspec', '~> 2.2', require: false
end

group :development do
  gem 'faker', '~> 2.18'
  gem 'graphiql-rails', '~> 1.7'
  gem 'listen', '~> 3.3'
  gem 'spring'
end

gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
