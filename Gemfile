source 'https://rubygems.org'

gem 'rails', '4.0.4'

gem 'foreman'
gem 'thin'

gem 'pg'

gem 'jquery-rails'

gem 'jbuilder', '~> 1.2'

group :assets do

	gem 'sass-rails', '~> 4.0.2'
	
	# Coffeescript for those gems that need it
	gem 'coffee-rails', '~> 4.0.0'
	
	gem 'uglifier', '>= 1.3.0'

end

group :development, :test do

	gem 'rspec-rails'
	gem 'guard-rspec'
	gem 'spork'
	gem 'guard-spork'

end

group :development do

	gem 'annotate'

	gem 'better_errors'
	gem 'binding_of_caller'

	gem 'meta_request'

	gem 'pry'
	gem 'pry-nav'

end

group :test do

	gem 'capybara'

	gem 'rb-fsevent', require: false
	gem 'growl'

	gem 'database_cleaner'

	gem 'fabrication'

	gem 'shoulda-matchers'
end

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end
