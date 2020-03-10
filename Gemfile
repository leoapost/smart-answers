source "https://rubygems.org"

ruby File.read(".ruby-version").chomp

gem 'rails', '~> 5'
gem "railties"
gem "sprockets-rails"

gem "govuk_app_config"

gem "ast"
gem "gds-api-adapters", "~> 63.5"
gem "govspeak", "~> 6.5.3"
gem "govuk-content-schema-test-helpers", "~> 1.6.1"
gem "govuk_publishing_components", "21.27.1"
gem "htmlentities", "~> 4"
gem "json"
gem "method_source"
gem "parser"
gem "plek", "3.0.0"
gem "rack_strip_client_ip"
gem "rails-i18n"
gem "rails_stdout_logging"
gem "sass-rails", "~> 5.0.7"
gem "slimmer", "~> 13.2.2"
gem "tilt", "2.0.10"
gem "uglifier"
gem "uk_postcode", "~> 2.1.5"

group :development do
  gem "better_errors"
  gem "binding_of_caller"
  gem "nokogiri"
end

group :development, :test do
  gem "byebug"
  gem "pry"
  gem "rspec-rails", "~> 3.9.1"
  gem "rubocop-govuk"
  gem "timecop"
end

group :test do
  gem "ci_reporter"
  gem "govuk_test"
  gem "minitest", "~> 5.14"
  gem "minitest-focus", "~> 1.1", ">= 1.1.2"
  gem "mocha", "1.11.2", require: false
  gem "rails-controller-testing"
  gem "shoulda", "~> 3.6.0"
  gem "simplecov", "~> 0.18.5", require: false
  gem "simplecov-rcov", "~> 0.2.3", require: false
  gem "webmock", "~> 3.8.2", require: false
end
