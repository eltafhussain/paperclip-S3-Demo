source "https://rubygems.org"

gem "rails", "~> 4.2.0"

gem "aws-sdk", "~> 2.3"
gem "coffee-rails"
gem "jquery-rails"
gem "paperclip"
gem "pg"
gem "sass-rails"
gem "uglifier"
gem 'tzinfo-data', platform: [:mingw,:mswin,:x64_mingw]

group :development do
  gem "web-console", "~> 2.0"
end

group :development, :test do
  gem "factory_girl_rails"
  gem "launchy"
  gem "rspec-rails"
end

group :test do
  gem "capybara"
  gem "shoulda-matchers", ">= 3.0.0", require: false
end
group :production do
  gem 'rails_12factor', '0.0.2'

  gem 'puma'
end
