source 'https://rubygems.org'

gem "activerecord", "~> #{ENV['AR_VERSION']}" if ENV['AR_VERSION']
if !defined?(JRUBY_VERSION)
gem "mysql2", "~> 0.3.18"
end

# Specify your gem's dependencies in activerecord-mysql-awesome.gemspec
gemspec
