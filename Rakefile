begin
  require 'bundler/setup'
rescue LoadError
  puts 'You must `gem install bundler` and `bundle install` to run rake tasks'
end

APP_RAKEFILE = File.expand_path("../spec/dummy/Rakefile", __FILE__)
load 'rails/tasks/engine.rake'
load 'rspec/rails/tasks/rspec.rake'

load "jshint/tasks/jshint.rake"

Peoplefinder::Engine.load_tasks

Bundler::GemHelper.install_tasks
