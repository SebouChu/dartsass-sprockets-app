source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.3"

gem "bootsnap", require: false
gem "bootstrap", github: "SebouChu/bootstrap-rubygem"
gem "dartsass-sprockets", "~> 3.0"
gem "dartsass-ruby", path: "../dartsass-ruby"
gem "jquery-rails", "~> 4.5"
gem "pg", "~> 1.1"
gem "puma", "~> 5.0"
gem "rails", "~> 7.0.4", ">= 7.0.4.2"
gem "simple_form", "~> 5.2"
gem "sprockets-rails"
gem "summernote-rails", github: "noesya/summernote-rails", branch: "fix/dart-sass"
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]

group :development, :test do
  gem "byebug", platforms: %i[ mri mingw x64_mingw ]
end

group :development do
  gem "web-console"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end
