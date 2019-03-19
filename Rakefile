require 'rubygems'
require 'rdoc/task'

task :default => :walk_the_path

task :in_darkness do
  cd 'koans'
  ruby 'path_to_enlightenment.rb darkness'
end

task :walk_the_path do
  cd 'koans'
  ruby 'path_to_enlightenment.rb'
end

Rake::RDocTask.new do |rd|
  rd.main = "README.rdoc"
  rd.rdoc_files.include("README.rdoc", "koans/*.rb")
end
