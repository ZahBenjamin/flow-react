source "https://rubygems.org"

# Core Rails Gems
gem "rails", "~> 7.2.1"
gem "sprockets-rails" # Asset pipeline for Rails
gem "sqlite3", ">= 1.4" # Default database for ActiveRecord
gem "puma", ">= 5.0" # Web server for Rails

# JavaScript and Front-End Frameworks
gem "jsbundling-rails" # Bundle and transpile JavaScript
gem "turbo-rails" # Hotwire SPA-like accelerator
gem "stimulus-rails" # Hotwire's JavaScript framework

# JSON APIs
gem "jbuilder" # Build JSON APIs easily

# Authentication
gem "devise", "~> 4.9" # User authentication

# Test and Development Tools
group :development, :test do
  gem "debug", platforms: %i[mri windows], require: "debug/prelude" # Debugging tools
  gem "rspec-rails", "~> 7.0" # RSpec testing framework
  gem "factory_bot_rails", "~> 6.4" # Fixtures replacement
  gem "faker", "~> 3.4" # Generate fake data for tests
  gem "pry-rails", "~> 0.3.11" # Enhanced REPL for Rails console
  gem "brakeman", require: false # Security scanner for Rails applications
  gem "rubocop-rails-omakase", require: false # Ruby/Rails code style guide
end

group :development do
  gem "web-console" # Rails console on error pages
end

group :test do
  gem "capybara" # System testing with Capybara
  gem "selenium-webdriver" # Browser automation for system tests
end

# Additional Production Tools
# gem "redis", ">= 4.0.1" # Redis adapter for Action Cable in production
# gem "kredis" # Higher-level data types in Redis
# gem "image_processing", "~> 1.2" # ActiveStorage variants for image processing

# View Components
gem "view_component", "~> 3.18" # Build reusable view components

# Platform-Specific Gems
gem "tzinfo-data", platforms: %i[windows jruby] # Timezone info for Windows and JRuby platforms

# Performance Optimization
gem "bootsnap", require: false # Speeds up boot times by caching expensive operations
