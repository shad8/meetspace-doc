require "rake/clean"

task :default => [:pdf]

SRC = "project.tex"

task :pdf do


  # sh "rm *.pdf"
  sh "pdflatex #{SRC}"
  sh "bibtex project"
  sh "makeindex project"
  # sh "rm *.aux *.lof *.log *.lot *.out *.toc"
  # sh "rm *.aux *.log *.out"

end
