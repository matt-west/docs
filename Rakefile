require 'html/proofer'

task :test do
  sh "bundle exec jekyll build"
  HTML::Proofer.new("./_site", { :href_ignore => ['127.0.0.1:4000'] }).run
end
