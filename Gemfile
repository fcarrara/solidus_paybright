source 'https://rubygems.org'

branch = ENV.fetch('SOLIDUS_BRANCH', 'master')
gem 'solidus', github: 'solidusio/solidus', branch: branch
# Provides basic authentication functionality for testing parts of your engine
gem 'solidus_auth_devise'

if branch < 'v2.0'
  gem 'rails_test_params_backport', group: :test
end

gemspec
