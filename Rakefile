$LOAD_PATH << "./lib"
require File.dirname(__FILE__) + "/lib/frank.rb"

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gemspec|
    gemspec.name = "frank"
    gemspec.summary = "Static Site Non-Framework"
    gemspec.description = "Rapidly develop static sites using any supported templating language"
    gemspec.version = Frank::VERSION
    gemspec.email = "travis.dunn@thisismedium.com"
    gemspec.homepage = "http://github.com/blahed/frank"
    gemspec.authors = ["blahed", "nwah"]
  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler not available. Install it with: gem install jeweler"
end