# Rakefile for a Jekyll static site
require 'rake'

desc "Build the site with Jekyll"
task :build do
  sh "bundle exec jekyll build"
end

desc "Serve the site locally"
task :serve do
  sh "bundle exec jekyll serve"
end

desc "Clean the site directory"
task :clean do
  sh "rm -rf _site"
end
