require 'rake/rdoctask'

desc 'Run rdoc task on test/ dir'
Rake::RDocTask.new(:test_rdoc) do |rd|
  rd.main = "test/README"
  rd.rdoc_files << "test/README"
  rd.rdoc_dir = 'test/doc'
end
