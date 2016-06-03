source 'https://rubygems.org'

gem 'locomotivecms_wagon', '~> 2.1.1'

# gem 'guard-livereload', '~> 2.5.1'

group :development do
  # Mac OS X
  gem 'rb-fsevent', '~> 0.9.1', require: 'rb-fsevent' if RUBY_PLATFORM.include?('darwin')

  # Unix
  gem 'therubyracer', require: 'v8', platforms: :ruby unless RUBY_PLATFORM.include?('darwin')

  gem 'rb-inotify', '~> 0.9', require: 'rb-inotify' if RUBY_PLATFORM.include?('linux')
end

group :misc do
end
