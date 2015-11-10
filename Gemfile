source 'https://rubygems.org'

# Specify your gem's dependencies in vagrant-cloner.gemspec
gemspec

group :development, :test do
  gem 'rspec'
  gem 'pry'
  gem "vagrant", git: "https://github.com/mitchellh/vagrant.git"
end

group :plugins do
  gem "vagrant-cloner", path: "."
end