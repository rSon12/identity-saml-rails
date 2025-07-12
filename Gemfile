source 'https://rubygems.org'

ruby '~> 2.6.5'

gem 'pg'
gem 'rails', '~> 7.1.0'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 6.0', '>= 6.0.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Turbolinks makes following links in your web application faster.
# Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

gem 'omniauth-saml', '>= 2.0.0'
gem 'ruby-saml', '>= 1.10.0'

group :deploy do
  gem 'capistrano' , '>= 3.10.2' # , '~> 3.4'
  gem 'capistrano-passenger', '>= 0.2.1'
  gem 'capistrano-rails' , '>= 1.4.0' # , '~> 1.1', require: false
end

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
  gem 'rspec-rails', '~> 3.8', '>= 3.8.2'
  gem 'saml_idp', git: 'https://github.com/18F/saml_idp.git', branch: 'master'
end

group :development do
  gem 'bummr', '>= 0.3.0', require: false
  gem 'reek'
  gem 'rubocop', '>= 0.52.1'
end

group :test do
  gem 'codeclimate-test-reporter', '>= 1.0.9', require: nil
  gem 'sinatra', '>= 2.0.5'
  gem 'webmock'
end

group :production do
  gem 'rails_12factor'
end
