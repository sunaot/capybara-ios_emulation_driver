require "bundler/gem_tasks"
require 'rake/testtask'

task 'default' => 'test'

Rake::TestTask.new do |t|
  t.libs << 'test/lib'
  t.test_files = FileList['test/**/test_*.rb', 'test/**/*_test.rb']
end
