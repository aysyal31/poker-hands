require 'rake/testtask'
Rake::TestTask.new do |t|
  t.libs = ['lib']
  t.verbose = true
  t.warning = true
end

Rake::TestTask.new do |t|
  t.libs = ['lib']
  t.name = 'test:integration'
  t.verbose = true
  t.warning = true

end

task :default => :test
