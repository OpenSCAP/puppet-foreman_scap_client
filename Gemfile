source 'https://rubygems.org'

if ENV.key?('PUPPET_VERSION')
  puppetversion = "~> #{ENV['PUPPET_VERSION']}"
else
  puppetversion = ['>= 5.5.8']
end

gem 'rake'
gem 'puppet', puppetversion
gem 'puppetlabs_spec_helper', '>= 0.8.0'
gem 'metadata-json-lint', :require => false
gem 'rspec-puppet-facts', '~> 1.7', :require => false
gem 'puppet-blacksmith', '>= 3.1.0', {"groups"=>["development"]}
