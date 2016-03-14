require 'rake'

desc 'Preview the site with Jekyll'
task :preview do
    sh "bundle exec jekyll serve"
end

desc 'Search site and print specific deprecation warnings'
task :check do 
    sh "jekyll doctor"
end
