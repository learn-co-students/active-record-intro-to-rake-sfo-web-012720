task :environment do
  require_relative './config/environment'
end

namespace :greeting do

  desc 'outputs hello to the terminal'
  task :hello do
  puts "hello from Rake!"
  end

  desc 'outputs hola to the terminal'
  task :hola do
  puts "hola de Rake!"
  end
end

desc 'console thing'
task :console do
return true
end

namespace :db do

  desc 'migrate or whatever'
  task :migrate => :environment do
    Student.create_table
  end

  desc 'seed the database with some dummy data'
  task :seed do
    require_relative './db/seeds.rb'
  end
end
  
