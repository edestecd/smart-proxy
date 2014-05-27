source 'https://rubygems.org'

ruby '1.9.3', :engine => 'ruby', :engine_version => '1.9.3', :patchlevel => '545'
#ruby=ruby-1.9.3-p545
#ruby-gemset=foremanproxy

gem 'json'
gem 'sinatra', '< 1.4.3'

Dir["#{File.dirname(__FILE__)}/bundler.d/*.rb"].each do |bundle|
 # puts "adding custom gem file #{bundle}"
  self.instance_eval(Bundler.read_file(bundle))
end
