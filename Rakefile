

namespace :greeting do
desc 'outputs hello to the terminal'
  task :hello do
    puts "hello from Rake!"
  end
  
  desc 'outputs hola to the terminal'
  task :hola do
    puts "hlola de Rake!"
  end
end

desc 'drop into the Pry console'
task :console => :environment do
  Pry.start
end