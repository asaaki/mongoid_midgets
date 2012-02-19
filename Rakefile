# encoding: utf-8
$LOAD_PATH.unshift File.expand_path("../lib", __FILE__)

require "rubygems"
require "bundler"
begin
  Bundler.setup(:default, :development)
rescue Bundler::BundlerError => e
  $stderr.puts e.message
  $stderr.puts "Run `bundle install` to install missing gems"
  exit e.status_code
end
require "rake"
require "jeweler"
require "mongoid_midgets"

Jeweler::Tasks.new do |gem|
  # gem is a Gem::Specification... see http://docs.rubygems.org/read/chapter/20 for more options
  gem.name = "mongoid_midgets"
  gem.version = MongoidMidgets::VERSION
  gem.homepage = "http://github.com/asaaki/mongoid_midgets"
  gem.license = "MIT"
  gem.summary = %Q{meta/dependency gem for mongoid microgems}
  gem.description = %Q{mongoid_midget is a meta/dependency gem for my microgems.}
  gem.email = "chris@dinarrr.com"
  gem.authors = ["Christoph Grabo"]
  # dependencies defined in Gemfile
end
Jeweler::RubygemsDotOrgTasks.new
