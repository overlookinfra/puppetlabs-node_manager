source "https://rubygems.org"
gem 'pry'

group :test do
  gem "rake"
#  gem "puppet", ENV['PUPPET_VERSION'] || '~> 3.7.3'
  gem "rspec-puppet", :git => 'https://github.com/rodjek/rspec-puppet.git'
  gem 'rspec-puppet-utils', :git => 'https://github.com/Accuity/rspec-puppet-utils.git'
  gem 'hiera-puppet-helper', :git => 'https://github.com/bobtfish/hiera-puppet-helper.git'
  # there seems to be a bug with puppet-blacksmith and metadata-json-lint
  # removing metadata for now
  gem "metadata-json-lint"
  gem 'puppet-syntax'
  gem 'puppet-lint'
  gem 'listen', '<= 3.0.8'
  gem 'net-http-persistent', '~> 2.9.4'
end

group :development do
  gem "travis"
  gem "travis-lint"
  gem "puppet-blacksmith"
  gem "guard-rake"
end

gem 'puppet', nil || ENV['PUPPET_VERSION']
gem 'puppetlabs_spec_helper'
gem 'webmock'
gem 'puppetclassify', '0.1.7'
