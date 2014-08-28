source 'https://rubygems.org'
source "https://rubygems.org"

gem "unicorn"
gem "rails", "~> 4.1.0"
gem "devise"
gem "exception_notification"
gem "newrelic_rpm"
gem "rails-i18n"

# mongoid 4
gem "mongoid", github: "mongoid"
gem "symbolize"

gem "sass-rails", "~> 4.0"
gem "uglifier", ">= 1.3"
gem "coffee-rails", "~> 4.0"
# gem "activeadmin", github: "gregbell/activeadmin", branch: "rails4"
# gem "activeadmin-mongoid", git: "https://github.com/iAmeen/activeadmin-mongoid.git"

gem 'rails_config'
gem "jquery-rails"
gem "jbuilder", "~> 1.2"
gem "therubyracer", platforms: :ruby
gem "less-rails"
# gem "twitter-bootstrap-rails"

gem "kaminari"
gem "haml-rails"

# wicked_pdf
gem "wkhtmltopdf-binary"
gem "wicked_pdf"

gem "mongoid-paperclip", :require => "mongoid_paperclip", github: "meskyanichi/mongoid-paperclip", branch: :master
gem "aws-sdk"

gem "rubyzip"
gem "delayed_job_mongoid"
gem "daemons" 

group :development do
  gem "capistrano", '~> 3.1'
  gem 'capistrano-rails'
  gem 'capistrano-bundler'
  gem 'capistrano-rbenv', '~> 2.0'
  gem "capistrano3-unicorn"

  gem "pry-rails"
  # gem "pry-exception_explorer"
  # gem "pry-nav"
end

group :test do
  gem "rspec-rails", '~> 3.0.0'
  gem "spork-rails"
  gem 'webmock'
end
