# Gemfile (完成版)

source 'https://rubygems.org'

git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.1.4'

# Railsの基本設定（安定版を使用）

gem 'rails', '~> 7.0.8'

gem 'sprockets-rails'

gem 'sqlite3', '~> 1.4'

gem 'puma', '~> 5.0'

gem 'importmap-rails'

gem 'turbo-rails'

gem 'stimulus-rails'

gem 'jbuilder'

gem 'bootsnap', require: false

gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

# 教材で指定されているgemを追加

gem 'sassc-rails'

group :development, :test do
  gem 'debug', platforms: %i[mri mingw x64_mingw]

  # 教材で指定されているgemを追加

   gem 'reline'
end

group :development do
   gem 'web-console'

   # 教材で指定されているgemを追加

   gem 'solargraph'

   gem 'irb'

   # このgemはirb 1.8.0以降で不要になったためコメントアウト

   # gem "repl_type_completor"
end

group :test do
   gem 'capybara'

   gem 'selenium-webdriver'

   # 教材で指定されているgemを追加

   gem 'webdrivers'

   gem 'rails-controller-testing'

   gem 'minitest'

   gem 'minitest-reporters'

   gem 'guard'

   gem 'guard-minitest'
end
