require 'html/proofer'

task :test do
  sh "bundle exec jekyll build"
  HTML::Proofer.new("./_site", { :href_ignore => ['http://localhost:4000/'] }).run
end
