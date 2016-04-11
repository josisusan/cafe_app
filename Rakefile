ENV['RACK_ENV'] ||= 'development'
env = ENV['RACK_ENV']
Bundler.require(:default, env.to_sym)
require 'rake'
require 'sinatra/activerecord/rake'
require './app'