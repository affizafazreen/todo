# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.

require File.expand_path('../config/application', __FILE__)
require 'rake'
# .. snip ..
require 'ci/reporter/rake/rspec'

Listr::Application.load_tasks

#task :travis => ['db:create:all', 'db:migrate', :default]
task :spec => 'ci:setup:rspec'
