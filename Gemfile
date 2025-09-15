path "../"
source 'https://rubygems.org'

group :development, :test do
  gem 'pry'
  gem 'pry-byebug'
  # stable forked version of active_model_serializers in order to write an integration test
  gem 'active_model_serializers', git: 'git@github.com:indiegogo/active_model_serializers.git', branch: '0-8-stable'

  # currently tested against 8.0
  gem 'railties', '~> 8.0'
  gem 'actionpack', '~> 8.0'
  gem 'activerecord', '~> 8.0'
end

gemspec
