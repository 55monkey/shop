source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.1.4'
# Use sqlite3 as the database for Active Record

# Use Puma as the app server
gem 'puma', '~> 3.7'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'

gem 'spree', '~> 3.4.4'
gem 'spree_auth_devise', '~> 3.3'
gem 'spree_gateway', '~> 3.3'
gem 'spree_paypal_express', github: 'spree-contrib/better_spree_paypal_express'

gem 'spree_mail_settings', github: 'spree-contrib/spree_mail_settings'

# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '~> 2.13.0'
  gem 'selenium-webdriver'
  gem 'sqlite3'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :production do
  gem 'pg', '~> 1.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
#gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem 'sprockets-helpers', '~> 1.2.1'
gem 'vinsol_spree_themes', github: 'vinsol-spree-contrib/spree_themes', branch: 'master'
gem 'figaro', '~> 1.1', '>= 1.1.1'
gem 'aws-sdk', '~> 3.0', '>= 3.0.1'

gem 'globalize', github: 'globalize/globalize'
gem 'spree_i18n', github: 'spree-contrib/spree_i18n'
gem 'spree_globalize', github: 'spree-contrib/spree_globalize', branch: 'master'
gem 'spree_static_content', github: 'spree-contrib/spree_static_content'
gem 'spree_recently_viewed', github: 'spree-contrib/spree_recently_viewed'
gem 'spree_email_to_friend', github: 'spree-contrib/spree_email_to_friend', branch: 'master'
gem 'spree_contact_us', :git => 'https://github.com/spree-contrib/spree_contact_us'