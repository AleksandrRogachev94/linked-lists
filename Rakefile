require_relative 'linked_list.rb'
require 'bundler'
Bundler.require
require 'irb'

task :console do
  @ll = LinkedList.new(Node.new(1))
  @ll.insertTail(Node.new(2))
  @ll.insertTail(Node.new(3))
  ARGV.clear
  IRB.start
end
