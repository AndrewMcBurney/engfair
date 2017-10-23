# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

ruby "2.4.1"

gem "dotenv-rails", require: "dotenv/rails-now"
gem "jbuilder", "~> 2.5"
gem "jquery-rails"
gem "pg", "~> 0.21.0"
gem "puma", "~> 3.0"
gem "rails", "~> 5.0.2"
gem "sass-rails", "~> 5.0"
gem "slim-rails", "~> 3.1"
gem "uglifier", ">= 1.3.0"
gem "validates_email_format_of"
gem "vital"

group :development, :test do
  gem "byebug", platform: :mri
  gem "foreman"
  gem "rspec-rails", "~> 3.5"
end

group :development do
  gem "listen", "~> 3.0.5"
  gem "pry"
  gem "rubocop"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
  gem "web-console", ">= 3.3.0"
end
