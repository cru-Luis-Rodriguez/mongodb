source 'https://rubygems.org'

gem 'berkshelf',  '~> 3.1.3'
gem 'chefspec',   '~> 4.0'
gem 'foodcritic', '~> 3.0'
gem 'rake',       '~> 10.1'
gem 'rubocop',    '~> 0.24.0'
gem 'kitchen-gce', '= 0.2'
gem 'thor-scmversion', '~> 1.7.0'
gem 'stove', '~> 3.2', '>= 3.2.3'
gem 'guard-kitchen'
group :integration do
    gem 'test-kitchen',    '~> 1.2'
    gem 'kitchen-vagrant', '~> 0.14'
end

group :test do
  gem "guard"
  gem "guard-rspec"
  gem "ruby_gntp"
  gem 'rb-inotify', :require => false
  gem 'rb-fsevent', :require => false
  gem 'rb-fchange', :require => false
end
