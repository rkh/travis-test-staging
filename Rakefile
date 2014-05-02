require 'rake'

task :hello_world do
  puts "RUBY_ENGINE: #{defined?(RUBY_ENGINE) ? RUBY_ENGINE : 'ruby'};"
  puts "RUBY_VERSION: #{RUBY_VERSION}"
  begin; require 'rubygems'; puts "GEM_ROOT: #{Gem.default_dir.inspect};"; rescue LoadError; end
end
