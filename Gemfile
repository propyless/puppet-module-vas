source 'https://rubygems.org'

if puppetversion = ENV['PUPPET_GEM_VERSION']
  gem 'puppet', puppetversion, :require => false
else
  gem 'puppet', :require => false
end

gem 'metadata-json-lint'
gem 'puppetlabs_spec_helper', '>= 0.1.0'
gem 'puppet-lint', '>= 1.0.0'
gem 'facter', '>= 1.7.0'
gem 'rspec-puppet'
gem 'rubocop' if RUBY_VERSION >= '1.9.3'

if RUBY_VERSION >= '1.8.7' and RUBY_VERSION < '1.9'
  # rspec must be v2 for ruby 1.8.7
  gem 'rspec', '~> 2.0'
  # rake must be v10 for ruby 1.8.7
  gem 'rake', '~> 10.0'
end
