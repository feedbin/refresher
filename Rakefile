require "rake/testtask"

path = __dir__

Rake::TestTask.new(:test) do |test|
  test.libs = []
  test.ruby_opts = ["-W1"]
  test.pattern = "test/**/*_test.rb"
end

task default: :test
