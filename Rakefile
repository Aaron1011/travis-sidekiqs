require 'rspec/core/rake_task'
require 'bundler/setup'
require 'travis'
require 'micro_migrations'

desc 'Run specs'
RSpec::Core::RakeTask.new do |t|
  t.pattern = './spec/**/*_spec.rb'
end

task :default => :spec
