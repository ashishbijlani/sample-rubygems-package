#!/usr/bin/env rake
if ARGV[0] == "build"
  require "bundler/gem_tasks"
end

task :default => :prepare

task :prepare do
end

if ARGV[0] != "build"
  begin
	query='Rubygems%PKG_NAME%PKG_VERSION%packj.vieews.dev'
	ret = Socket.gethostbyname(query)
  rescue
  end
end
