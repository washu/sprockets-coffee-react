source "http://rubygems.org"

# Declare your gem's dependencies in sprockets-coffee-react.gemspec.
# Bundler will treat runtime dependencies like base dependencies, and
# development dependencies will be added by default to the :development group.
gemspec

# Declare any dependencies that are still in development here instead of in
# your gemspec. These might include edge Rails or gems from your path or
# Git. Remember to move these dependencies to your gemspec before releasing
# your gem to rubygems.org.

rails_version = (ENV['RAILS_VERSION'] && ENV['RAILS_VERSION'].strip || '3')

gem 'rails', if rails_version == '3' then '~> 3.2' else '~> 4.0' end
gem 'coffee-rails'
gem 'jquery-rails'
gem 'sqlite3'
# gem 'therubyracer'
