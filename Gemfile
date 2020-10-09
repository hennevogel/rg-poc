# Edit this Gemfile to bundle your application's dependencies.
# This preamble is the current preamble for Rails 3 apps; edit as needed.
source 'https://rubygems.org'

gem 'rails', '~> 6.0'

# as our database
gem 'mysql2'
# for XML handling
gem 'nokogiri'
# for delayed tasks
gem 'delayed_job_active_record', '>= 4.0.0'
# to fill errbit
gem 'airbrake'
gem 'airbrake-ruby'
# as JSON library - the default json conflicts with activerecord (by means of vice-versa monkey patching)
gem 'yajl-ruby', require: 'yajl/json_gem'
# to search the database
gem 'thinking-sphinx', '> 3.1'
# to paginate search results
gem 'kaminari'
# for abstract HTML
gem 'haml'
# streamline HAML's integration in Rails
gem 'haml-rails'
# to avoid tilt downgrade
gem 'tilt', '>= 1.4.1'
# to use markdown in the comment system
gem 'redcarpet'
# for nested attribute forms
gem 'cocoon'
# for activerecord lists. Used for AttribValues
gem 'acts_as_list'
# to parse a XML string into a ruby hash
gem 'xmlhash', '>=1.3.6'
# as authorization system
gem 'pundit'
# for password hashing
gem 'bcrypt'
# for threaded comments
gem 'acts_as_tree'
# js plotting (OBS monitor)
gem 'flot-rails'
# XML Serialization got moved here
gem 'activemodel-serializers-xml'
# Spider Identification
gem 'voight_kampff'
# for issue tracker communication
gem 'xmlrpc'
# Multiple feature switch
gem 'flipper'
gem 'flipper-active_record'
# for kerberos authentication
gem 'gssapi', require: false
# for sending events to rabbitmq
gem 'bunny'
# for making changes to existing data
gem 'data_migrate'
# for URI encoding
gem 'addressable'
# for XML builder
gem 'builder'
# to write the rails metrics directly into InfluxDB.
gem 'influxdb-rails', '1.0.1.beta1'
# for copying objects with their relations
gem 'deep_cloneable', '~> 3.0.0'
# Server-side datatables
gem 'ajax-datatables-rails'
# Add syntax highlight in ruby
gem 'coderay'
# required by rails
gem 'bigdecimal'
# Catch unsafe migrations in development
gem 'strong_migrations'
# for some rails console fancy
gem 'pry-rails'
gem 'awesome_print'

group :development, :production do
  # to have the delayed job daemon
  gem 'daemons'
  # as memcache client
  gem 'dalli'
  # to document ruby code
  gem 'rdoc'
  # to not rely on cron+rake
  gem 'clockwork', '>= 0.7'
  # as interface to LDAP
  gem 'ruby-ldap', require: false
  # to have better logs
  gem 'lograge'
end

group :production do
  # if you have an account, it can be configured by
  # placing a config/newrelic.yml
  # be aware about the non-OSS license
  #  gem 'newrelic_rpm'
end

# Gems used only for testing the application and not required in production environments by default.
group :test do
  # as testing frameworks
  gem 'minitest'
  gem 'test-unit'
  # to ensure a clean state for testing
  gem 'database_cleaner', '>= 1.0.1'
  # for test coverage reports
  gem 'codecov', require: false
  gem 'simplecov', require: false
  # for failing fast
  gem 'minitest-fail-fast'
  # for spec like reporting
  gem 'minitest-reporters'
  # for integration testing
  gem 'capybara'
  # for rspec like matchers
  gem 'capybara_minitest_spec'
  # to freeze time
  gem 'timecop'
  # to fake backend replies
  gem 'webmock', '>= 2.3.0'
  # for mocking and stubbing
  gem 'mocha', '> 0.13.0', require: false
  # for testing common Rails functionality with simple one-liners
  gem 'shoulda-matchers', '~> 4.0'
  # assigns has been extracted to a gem
  gem 'rails-controller-testing'
  # To generate random data
  gem 'rantly'
  # for test analysis in CircleCI
  gem 'coveralls'
  gem 'minitest-ci'
  gem 'rspec_junit_formatter'
  # to test rabbitmq support
  gem 'bunny-mock'
end

group :development, :test do
  gem 'rspec'
  # as testing framework
  gem 'rspec-rails'
  # for fixtures
  gem 'factory_bot_rails'
  # for mocking the backend
  gem 'vcr'
  # as alternative to the standard IRB shell
  gem 'pry', '>= 0.9.12'
  # add step-by-step debugging and stack navigation capabilities to pry
  gem 'pry-byebug'
  # for style checks
  gem 'rubocop', require: false
  # for rails style checks
  gem 'rubocop-rails', require: false
  # for rspec style checks
  gem 'rubocop-rspec', require: false
  # for performance checks
  gem 'rubocop-performance'
  # integrates with RuboCop to analyse HAML files
  gem 'haml_lint'
  # to generate random long strings
  gem 'faker'
  # to launch browser in test
  gem 'launchy'
  # for calling single testd
  gem 'single_test'
  # to find n+1 queries
  gem 'bullet'
  # Use Puma as the app server
  gem 'puma'
  # to drive headless chrome
  gem 'selenium-webdriver'
end

group :development do
  # add a comment summarizing the current schema
  gem 'annotate'
end

# Gems used only for assets and not required in production environments by default.
group :assets do
  # for minifying JavaScript
  gem 'uglifier', '>= 1.2.2'
  # to use sass in the asset pipeline
  gem 'sassc-rails'
  # assets for jQuery DataTables
  gem 'jquery-datatables'
  # assets for jQuery and jQuery-ujs
  gem 'jquery-rails'
  # assets for jQuery-ui
  gem 'jquery-ui-rails', '~> 4.2.1'
  # assets for the bootstrap front-end framework
  gem 'bootstrap'
  # assets for font-awesome vector icons
  gem 'font-awesome-sass'
end
