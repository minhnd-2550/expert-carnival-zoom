source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "2.7.2"
gem "rails", "~> 7.0.3"

gem "puma", "~> 5.0"
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]
gem "bootsnap", require: false
gem "devise"
gem "devise-jwt"
gem "rack-cors"
gem "config"
gem "http"
gem "redis"

group :development, :test do
  gem "sqlite3", "~> 1.4"
  gem "pry-rails"
end

group :production do
  gem "pg"
end
