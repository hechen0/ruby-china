if ENV['USE_OFFICIAL_GEM_SOURCE']
  source 'https://rubygems.org'
else
  source 'https://gems.ruby-china.org'
end

ruby '2.3.0'

gem 'rails', '5.0.0.beta3'
gem 'sprockets'
gem 'sass-rails'
gem 'coffee-rails'
gem 'uglifier'
gem 'jquery-rails'
gem 'jbuilder'
gem 'turbolinks', git: 'https://github.com/turbolinks/turbolinks-classic.git'
gem 'jquery-turbolinks'
gem 'dropzonejs-rails'

gem 'pg'

gem 'rack-attack'

gem 'rails-i18n'
gem 'http_accept_language'
gem 'rails_autolink'
gem 'md_emoji'

# OAuth Provider
gem 'doorkeeper', '4.0.0.rc2'
gem 'doorkeeper-i18n'

gem 'bulk_insert', git: 'https://github.com/huacnlee/bulk_insert.git', branch: 'fix/active-record-5-warning'

# 上传组件
gem 'carrierwave'
gem 'carrierwave-upyun'
gem 'mini_magick'

# 验证码，头像
gem 'rucaptcha'
gem 'letter_avatar'

# 用户系统
gem 'devise', '~> 4.0.0.rc1'
gem 'devise-encryptable'

# 通知系统
gem 'notifications'
gem 'ruby-push-notifications'

# 分页
gem 'will_paginate'

# 搜索
gem 'elasticsearch-model'
gem 'elasticsearch-rails'

# 三方平台 OAuth 验证登陆
gem 'omniauth'
gem 'omniauth-github'

# Permission
gem 'cancancan', '~> 1.13.1'

# Redis
gem 'redis'
gem 'hiredis'
gem 'redis-namespace'
gem 'redis-objects'

# Cache
gem 'second_level_cache', '2.2.2'

# Setting
gem 'rails-settings-cached'

# Markdown
gem 'redcarpet', '~> 3.3.4'
gem 'rouge', '~> 1.8.0'
gem 'auto-space'

# 队列
gem 'sidekiq'
# Sidekiq Web
gem 'sinatra', git: 'https://github.com/sinatra/sinatra.git', require: false

# 分享功能
gem 'social-share-button'

# 表单
gem 'simple_form'

# API
gem 'active_model_serializers', '0.10.0.rc5'

# Mailer Service
gem 'postmark'
gem 'postmark-rails'

# Dalli, kgio is for Dalli
gem 'kgio'
gem 'dalli'

gem 'puma'

# API cors
gem 'rack-cors', require: 'rack/cors'
gem 'rack-utf8_sanitizer'

# Mini profiler
gem 'rack-mini-profiler', require: false

gem 'oneapm_rpm'
gem 'exception_notification'
gem 'status-page'

group :development do
  gem 'capistrano', '2.9.0', require: false
  gem 'rvm-capistrano', require: false
  gem 'capistrano-sidekiq'
  gem 'derailed'
  # Better Errors
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'spring'
  gem 'spring-commands-rspec'
end

group :development, :test do
  gem 'rubocop', '~> 0.39.0', require: false
  gem 'rspec-rails', '3.5.0.beta1'
  gem 'factory_girl_rails', '~> 4.5.0'
  gem 'database_cleaner'
  gem 'capybara'
  gem 'jasmine-rails', '~> 0.10.2'
  gem 'letter_opener'

  gem 'codecov', require: false
  gem 'bundler-audit', require: false
  gem 'pry-byebug'
end
