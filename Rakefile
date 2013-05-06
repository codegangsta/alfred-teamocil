require "fileutils"

WORKFLOW_HOME = File.expand_path("~/Library/Application Support/Alfred 2/Alfred.alfredpreferences/workflows")


task :default => [:install]

task :install do
  puts "Installing teamocil workflow..."
  FileUtils.cp_r "teamocil", WORKFLOW_HOME
  puts "Done"
end


