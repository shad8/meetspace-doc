require "rake/clean"

task :default => [:pdf]

SRC = "project.tex"

task :pdf do
  sh "pdflatex #{SRC}"
  sh "bibtex project"
  sh "makeindex project"
end
