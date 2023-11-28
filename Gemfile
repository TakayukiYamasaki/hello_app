source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.2.2"

gem "rails", "~> 7.0.4", ">= 7.0.4.3"
gem "image_processing",           "1.12.2"
gem "active_storage_validations", "0.9.8"
gem "bcrypt",                     "3.1.18"
gem "faker",                      "2.21.0"
gem "will_paginate",              "3.3.1"
gem "bootstrap-will_paginate",    "1.0.0"
gem "bootstrap-sass",             "3.4.1"
gem "sassc-rails",                "2.1.2"
gem "sprockets-rails",            "3.4.2"
gem "importmap-rails",            "1.1.5"
gem "turbo-rails",                "1.4.0"
gem "stimulus-rails",             "1.2.1"
gem "jbuilder",                   "2.11.5"
gem "puma",                       "5.6.5"

gem "pg", "~> 1.1"
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]
gem "bootsnap", require: false

group :development, :test do
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
end

group :development do
  gem "web-console"
  gem "solargraph",  "0.48.0"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver",       "4.15.0"
  gem "webdrivers",               "5.2.0"
  gem "rails-controller-testing", "1.0.5"
  gem "minitest",                 "5.18.0"
  gem "minitest-reporters",       "1.6.0"
  gem "guard",                    "2.18.0"
  gem "guard-minitest",           "2.4.6"
end