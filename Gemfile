#!ruby
source ENV['GEM_SOURCE'] || 'https://rubygems.org'

if ENV.key?('PUPPET_VERSION')
  puppetversion = "= #{ENV['PUPPET_VERSION']}"
else
  puppetversion = ['>= 2.7']
end



gem 'puppet', puppetversion
gem 'rake'
gem 'puppet-lint'
gem 'rspec-puppet'

