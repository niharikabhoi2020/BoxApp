source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.5'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.0', '>= 6.0.2.1'
# Use postgresql as the database for Active Record
gem 'pg', '~> 1.2', '>= 1.2.2'
# Use Puma as the app server
gem 'puma', '~> 3.11'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use ActiveStorage variant
# gem 'mini_magick', '~> 4.8'

gem 'rb-readline'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
# gem 'rack-cors'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'database_cleaner', '~> 1.7'
  gem 'factory_bot_rails', '~> 5.1', '>= 5.1.1'
  gem 'faker', '~> 2.10', '>= 2.10.1'
  gem 'rspec', '~> 3.9'
  gem 'rspec-rails', '~> 3.9'
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  #The Bullet gem is designed to increase the application's performance by reducing the number of queries it makes. Read more: https://github.com/flyerhzm/bullet
  gem 'bullet'
  #Brakeman is a static analysis tool which checks Ruby on Rails applications for security vulnerabilities. Read more: https://github.com/presidentbeef/brakeman
  gem 'brakeman'
end

group :test do
  gem 'simplecov', require: false
end


# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem 'rollbar'
