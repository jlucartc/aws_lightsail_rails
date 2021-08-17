require "capistrano/setup"
require "capistrano/deploy"

require 'capistrano/rails' # sobe migrations
require "capistrano/bundler" # instala gems
require "capistrano/rvm" # configura o caminho correto para o bundle
require 'capistrano/passenger' # executa task de restart do passenger

require "capistrano/scm/git"
install_plugin Capistrano::SCM::Git

# Load custom tasks from `lib/capistrano/tasks` if you have any defined
Dir.glob("lib/capistrano/tasks/*.rake").each { |r| import r }
